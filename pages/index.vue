<template>
  <div>
    <div class="px-2 grid lg:grid-cols-2 pt-32 md:pt-48 pb-6 md:pb-32 md:flex-row flex-col m-auto max-w-6xl">
      <div class="mb-6 md:mb-0 mx-2 py-12 text-center md:text-left">
        <h1 class="text-5xl mb-2">This is title</h1>
        <p class="mb-2 text-gray-700">Lorem ipsum dolor sit amet consectetur adipisicing elit. Cum ipsumquidem nisi repellat voluptatibus nesciunt nemo ratione hic placeatbeatae.</p>
        <button class="bg-blue-700 text-white py-1 px-2 rounded-sm mt-2 hover:bg-blue-800">Click here</button>
      </div>
      <div class="w-1/2 md:w-full m-auto">
        <img src="../assets/img/content_team.svg" alt="coffee">
      </div>
    </div>
    <div class="m-auto max-w-6xl">
      <div class="px-2 flex justify-between md:flex-row flex-col-reverse py-12 md:py-32">
        <div class="w-1/2 md:flex-1 my-5 md:mb-0 md:mr-12 md:text-left m-auto  hidden md:block">
          <img src="../assets/img/building_website.svg" alt="coffee">
        </div>
        <div class="flex-1 m-5 md:m-0"> 
          <h5 class="text-3xl mb-3">Title</h5>
          <p class="mb-2 text-gray-700">Lorem ipsum dolor sit amet consectetur adipisicing elit. Saepe, deleniti illum! Minus provident a nemo quia magni non beatae accusamus ipsam quisquam, ut, dolor eum ad autem voluptatum corrupti nulla sunt explicabo! Laudantium quasi quidem unde assumenda ipsu FooterCompm quo eos blanditiis facere quod tempore necessitatibus cupiditate numquam, hic veniam esse?</p>
          <p class="text-gray-700">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam ad minus dolor suscipit praesentium itaque pariatur iure in sint explicabo quasi architecto ullam eaque hic harum est, quas alias laborum.</p>
        </div>
      </div>  
      <div class="px-2 sm:px-12 md:px-0 pb-24">
        <h4 class="text-black-50 text-4xl mb-8 text-center">Title Here</h4>
        <div class="grid lg:grid-cols-3 gap-10">
          <div class="my-5 shadow flex flex-col justify-center p-5">
            <h5 class="text-2xl text-blue-900 font-medium text-center">Title</h5>
            <img src="../assets/img/Photos.svg" alt="coffee" class="m-auto mb-5 w-3/6 md:w-9/12">
            <p class="text-gray-700 bg-white mb-2 text-justify">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ex hic quos deleniti tenetur cupiditate facilis porro at, saepe, fugiat minima ipsum necessitatibus optio maxime laudantium! Blanditiis vel perspiciatis fuga accusamus.</p>
            <button class="bg-blue-700 text-white py-1 rounded-sm mt-2 hover:bg-blue-800 w-full m-auto">Click Me</button>
          </div>
          <div class="my-5 shadow flex flex-col justify-center p-5">
              <h5 class="text-2xl text-blue-900 font-medium text-center">Title</h5>
              <img src="../assets/img/Photos.svg" alt="coffee" class="m-auto mb-5 w-3/6 md:w-9/12">
              <p class="text-gray-700 bg-white mb-2 text-justify">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ex hic quos deleniti tenetur cupiditate facilis porro at, saepe, fugiat minima ipsum necessitatibus optio maxime laudantium! Blanditiis vel perspiciatis fuga accusamus.</p>
              <button class="bg-blue-700 text-white py-1 rounded-sm mt-2 hover:bg-blue-800 w-full m-auto">Click Me</button>
          </div>
          <div class="my-5 shadow flex flex-col justify-center p-5">
              <h5 class="text-2xl text-blue-900 font-medium text-center">Title</h5>
              <img src="../assets/img/Photos.svg" alt="coffee" class="m-auto mb-5 w-3/6 md:w-9/12">
              <p class="text-gray-700 bg-white mb-2 text-justify">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ex hic quos deleniti tenetur cupiditate facilis porro at, saepe, fugiat minima ipsum necessitatibus optio maxime laudantium! Blanditiis vel perspiciatis fuga accusamus.</p>
              <button class="bg-blue-700 text-white py-1 rounded-sm mt-2 hover:bg-blue-800 w-full m-auto">Click Me</button>
          </div>
        </div>     
      </div>      
    </div>
    <div class="py-12 bg-white bg-gray-100">
        <div class="m-auto max-w-6xl text-center px-5 md:px-0">
          <h4 class="text-3xl mb-2">Something here</h4>
          <p class="text-gray-800 mb-4 w-full md:w-3/4 m-auto">Lorem, ipsum dolor sit amet consecteturadipisicing elit. Dolorum reprehenderit dolores provident harum underatione deleniti hic, quia ipsum necessitatibus rem molestiae. Enim,non aut!</p>
          <button class="bg-blue-700 text-white py-2 px-3 rounded-sm mt-2 hover:bg-blue-800">Click here</button>
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
      title: 'Homepage',
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
