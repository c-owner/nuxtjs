<template>
    <div class="container mx-auto grid grid-cols-9 mt-5 gap-5">
        <aside class="col-span-2">
            <!-- sidebar -->
            <div class="shadow-md shadow-black mt-5 border p-5 rounded text-center">
                <p class="text-3xl font-bold">{{ airport.abbreviation }}</p>
                <p>An airport located in {{ airport.city }}, {{ airport.state }}</p>
            </div>
        </aside>
        <main class="col-span-7">
            <!-- main content -->
            <h1 class="text-3xl font-bold mt-5">{{ airport.name }}</h1>
            <Nuxt/>
        </main>
    </div>
</template>

<script>
import airports from '~/data/airport.js'

export default {
    computed: {
        airport() {
            return airports.filter(airport => airport.abbreviation === this.$route.params.code.toUpperCase())[0]
        }
    }
}
</script>
