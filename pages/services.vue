<template>    
    <div>  
        <div class="m-auto max-w-6xl">
            <div class="px-2 pt-32 md:pt-48 grid grid-cols-1 md:grid-cols-2">
                <div>
                <h2 class="text-3xl mb-3">This is Title</h2>
                <p class="text-gray-800 mb-2">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Iusto cumque vero laudantium obcaecati, magnam deserunt dignissimos laboriosam inventore, eaque commodi ad, accusamus cupiditate nostrum vel.</p>
                 <p class="text-gray-800">Lorem ipsum dolor sit amet consectetur adipisicing elit. Nesciunt aliquam veritatis quasi neque, modi ut iusto reprehenderit magni illum quae!</p>
                </div>
                <div class="hidden md:block">
                <img src="../assets/img/Posts.svg" alt="mail" class="w-4/5 m-auto">
                </div>
            </div>
            <div class="px-2 py-48">
                <h2 class="mb-12 text-3xl text-center">Our Services</h2>
                <div class="grid lg:grid-cols-3 gap-10 text-center">
                    <div class="shadow p-5 mx-5 md:mx-0">
                        <img src="../assets/img/Photos.svg" alt="img" class="w-4/5 m-auto mb-2">
                        <span class="block text-2xl">Title</span>
                        <p class="my-3 text-gray-700">Lorem ipsum dolor sit amet consectetur adipisicing elit. Totam, impedit?</p>
                        <span class="block text-blue-700 font-bold">09-XXX-XXX-XX</span>
                    </div>
                    <div class="shadow p-5 mx-5 md:mx-0">
                        <img src="../assets/img/Photos.svg" alt="img" class="w-4/5 m-auto mb-2">
                        <span class="block text-2xl">Title</span>
                        <p class="my-3 text-gray-700">Lorem ipsum dolor sit amet consectetur adipisicing elit. Totam, impedit?</p>
                        <span class="block text-blue-700 font-bold">09-XXX-XXX-XX</span>
                    </div>
                    <div class="shadow p-5 mx-5 md:mx-0">
                        <img src="../assets/img/Photos.svg" alt="img" class="w-4/5 m-auto mb-2">
                        <span class="block text-2xl">Title</span>
                        <p class="my-3 text-gray-700">Lorem ipsum dolor sit amet consectetur adipisicing elit. Totam, impedit?</p>
                        <span class="block text-blue-700 font-bold">09-XXX-XXX-XX</span>
                    </div>
                </div>
            </div>
        </div>
        <footerComp />
    </div>
</template>

<script>
import footerComp from '../components/footerComp'

export default {
    components:{
        footerComp
    },
    head(){
    return{
      title: 'Services Page',
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: 'Landing Page'
        }      
      ]
    }
  }
}
</script>
