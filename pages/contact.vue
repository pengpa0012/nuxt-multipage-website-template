<template>
  <div>
    <div class="m-auto max-w-6xl">
      <div class="px-2 pt-32 md:pt-48 grid grid-cols-1 md:grid-cols-2">
        <div>
          <h2 class="text-3xl mb-3">This is Title</h2>
          <p class="text-gray-800 mb-2">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Iusto cumque vero laudantium obcaecati, magnam deserunt dignissimos laboriosam inventore, eaque commodi ad, accusamus cupiditate nostrum vel.</p>
          <ul class="text-gray-800">
            <li class="mb-1 hover:text-blue-800 cursor-pointer">List 1</li>
            <li class="mb-1 hover:text-blue-800 cursor-pointer">List 2</li>
            <li class="mb-1 hover:text-blue-800 cursor-pointer">List 3</li>
          </ul>
        </div>
        <div class="hidden md:block">
          <img src="../assets/img/Mailbox.svg" alt="mail" class="w-2/4 m-auto">
        </div>
      </div>
      <div class="px-2 py-56">
        <h2 class="text-3xl mb-5 text-center">Contact Us</h2>
        <div class="w-full md:w-4/5 m-auto">
          <form class="flex flex-col text-lg"> 
            <div class="flex">
              <input type="text" placeholder="Name" class="border-2 border-solid border-gray-600 focus:border-gray-900 outline-none w-full rounded mr-2 mb-2 p-2">
              <input type="text" placeholder="Last Name" class="border-2 border-gray-600 focus:border-gray-900 outline-none w-full rounded mb-2 p-2">
            </div>
            <input type="email" placeholder="Email Address" class="border-2 border-gray-600 focus:border-gray-900 outline-none rounded mb-2 p-2">
            <textarea placeholder="Message" class="border-2 border-solid border-gray-600 focus:border-gray-900 outline-none rounded mb-2 p-2"></textarea>
            <input type="submit" value="Send" class="border-gray-800 rounded mb-2 p-2 w-1/2 cursor-pointer bg-blue-800 text-white hover:bg-blue-900 outline-none">
          </form>
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
      title: 'Contact Page',
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