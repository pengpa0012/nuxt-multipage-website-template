<template>
    <div class="shadow fixed bg-white top-0 inset-x-0">
        <nav class="max-w-6xl m-auto flex justify-between items-center py-5">
            <div class="w-full md:w-auto text-xl mx-2 flex items-center justify-between z-10 md:z-1">
                <h1>Website Name</h1>
                <div class="block md:hidden cursor-pointer" @click.prevent="toggleNav">
                    <img src="../assets/img/nav-burger.svg" alt="nav">
                </div>
            </div>
            <ul :class="{'isActive' : isActive}" class="hidden md:flex text-lg flex-col md:flex-row absolute md:static bg-white shadow md:shadow-none inset-x-0 top-0 pt-16 md:pt-0" @click.prevent="closeNav">
                <nuxt-link to="/" class="py-2 md:py-0 px-1 mx-4 cursor-pointer  hover:text-blue-500 text-gray-700">Home</nuxt-link>
                <nuxt-link to="/contact" class="py-2 md:py-0 px-1 mx-4 cursor-pointer hover:text-blue-500 text-gray-700">Contact</nuxt-link>
                <nuxt-link to="/services" class="py-2 md:py-0 px-1 mx-4 cursor-pointer hover:text-blue-500 text-gray-700">Services</nuxt-link>
                <nuxt-link to="/about" class="py-2 md:py-0 px-1 mx-4 cursor-pointer hover:text-blue-500 text-gray-700">About</nuxt-link>
            </ul>
            <div class="hidden md:flex">
                <input type="text" placeholder="Search" class="border-2 border-solid border-gray-600 focus:border-gray-900
                rounded py-1 text-gray-700 px-2 border-r-0 -mr-1 outline-none">
                <div class="px-3 bg-blue-800 hover:bg-blue-900 cursor-pointer rounded-r flex">
                    <img src="../assets/img/search.svg" alt="search icon">
                </div>             
            </div>
        </nav>
    </div>
</template>

<style scoped>

    .isActive{
        display: flex;
    }

</style>

<script>

export default {
    name: 'navBar',
    data(){
        return{
            isActive: false
        }
    },
    methods :{
        toggleNav(){
            this.isActive = !this.isActive
        },
        closeNav(){
            this.isActive = !this.isActive
            console.log('test')
        }
    }
}

</script>