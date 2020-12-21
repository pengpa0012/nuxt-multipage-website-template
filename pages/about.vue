<template>
    <div>
      <div class="m-auto max-w-6xl">
        <div class="px-2 grid lg:grid-cols-2 pt-32 md:pt-48 pb-6 md:pb-32">
          <div class="mb-6 md:mb-0 md:mr-6 mx-2 py-12 text-center md:text-left">
            <h1 class="text-5xl mb-2">About Us</h1>
            <p class="mb-2 text-gray-700">Lorem ipsum dolor sit amet consectetur adipisicing elit. Cum ipsumquidem nisi repellat voluptatibus nesciunt nemo ratione hic placeatbeatae.</p>
            <p class="text-gray-700">Lorem ipsum dolor sit amet consectetur adipisicing elit. Cum ipsumquidem nisi repellat voluptatibus nesciunt nemo ratione hic placeatbeatae.</p>
          </div>
          <div>
            <img src="../assets/img/Online_page.svg" alt="coffee" class="w-1/2 md:w-full m-auto">
          </div>
        </div>
        <div class="px-2 py-6 md:py-48 flex flex-col">
          <h5 class="mb-12 text-3xl text-center">Our Team</h5>
          <div class="grid lg:grid-cols-3 gap-10">
            <div class="shadow mx-3 md:mx-0">
              <img src="../assets/img/person-1.jpg" alt="img" class="w-full">
              <div class="py-6 px-5">
                <span class="block text-xl">Thomas John</span>
                <span class="block mb-2 text-blue-700 font-bold">Founder</span>
                <p class="text-gray-700">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Magni eos molestiae suscipit pariatur magnam unde.</p>
              </div>          
            </div>
            <div class="shadow mx-3 md:mx-0">
              <img src="../assets/img/person-2.jpg" alt="img" class="w-full">
              <div class="py-6 px-5">
                <span class="block text-xl">James Carl</span>
                <span class="block mb-2 text-blue-700 font-bold">Co-founder</span>
                <p class="text-gray-700">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Magni eos molestiae suscipit pariatur magnam unde.</p>
              </div>   
            </div>
            <div class="shadow mx-3 md:mx-0">
              <img src="../assets/img/person-3.jpg" alt="img" class="w-full">
              <div class="py-6 px-5">
                <span class="block text-xl">Angela Smith</span>
                <span class="block mb-2 text-blue-700 font-bold">Vice President</span>
                <p class="text-gray-700">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Magni eos molestiae suscipit pariatur magnam unde.</p>
              </div>   
            </div>
          </div>
        </div>
        <div class="py-24 px-2 grid lg:grid-cols-2">
          <div class="mb-10 md:mb-5 mr-0 md:mr-10">
            <h6 class="text-xl mb-3">Something here...</h6>
            <p class="mb-1 text-gray-700">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatibus fugit officiis quos ad dignissimos perspiciatis delectus nobis blanditiis sapiente similique, adipisci, consequuntur repellendus, alias distinctio?</p>
            <p class="text-gray-700">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Cum facere saepe nesciunt ipsum repellat modi.</p>
          </div>
          <div class="ml-0 md:ml-10 grid lg:grid-cols-3 gap-10">
            <div class="mb-5 md:mb-0">
              <h5 class="text-xl mb-2">Title Here</h5>
              <ul>
                <li class="text-gray-800">List 1</li>
                <li class="text-gray-800">List 2</li>
                <li class="text-gray-800">List 3</li>
                <li class="text-gray-800">List 4</li>
                <li class="text-gray-800">List 5</li>
              </ul>
            </div>
            <div class="mb-5 md:mb-0">
              <h5 class="text-xl mb-2">Title Here</h5>
              <ul>
                <li class="text-gray-800">List 1</li>
                <li class="text-gray-800">List 2</li>
                <li class="text-gray-800">List 3</li>
                <li class="text-gray-800">List 4</li>
                <li class="text-gray-800">List 5</li>
              </ul>
            </div>
            <div class="mb-5 md:mb-0">
              <h5 class="text-xl mb-2">Title Here</h5>
              <ul>
                <li class="text-gray-800">List 1</li>
                <li class="text-gray-800">List 2</li>
                <li class="text-gray-800">List 3</li>
                <li class="text-gray-800">List 4</li>
                <li class="text-gray-800">List 5</li>
              </ul>
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
      title: 'About Page',
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