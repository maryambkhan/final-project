<template>
<div>
<TheHeader />
<main>
    <div class="text-center mt-4">
    <h1 class="sm:text-2xl font-serif md:text-4xl  lg:text-4xl mb-4">Contact</h1>
    <div class="sm:text-sm md:text-lg">
    <p>Have a question?</p>
    <p>Thinking about booking a session?</p>
    <p>Please do not hesitate to reach out if you have any questions.</p>
    </div>
    </div>
    <!--form-->
     <section class="mx-auto mt-2 bg-gray-300 max-w-6xl py-20 px-12 lg:px-24">
  <form action="https://formspree.io/f/mrgjyaed" method="POST"  class="flex justify-center">
    <fieldset>
        <!--first name-->
           
     <div class="-mx-3 md:flex">
      <div>
        <label for="user" class="after:content-['*'] after:ml-0.5 after:text-red-700 block text-lg  text-slate-700 font-bold">First Name</label>
        <input type="text" name="firstname" id="user"  required="" class=" mt-2 px-3 py-2 bg-white rounded-md border  border-slate-500  ml-2" >
        </div>
        
      <!--last name-->
        <div class="md:w-1/2">
        <label for="user" class=" after:content-['*'] after:ml-0.5 after:text-red-700 block text-lg  text-slate-700 font-bold">Last Name</label>
        <input type="text" name="lastname" id="lastname"  required="" class="mt-2 px-3 py-2 bg-white rounded-md border border-slate-500  ml-2 " >
      </div>
        </div>

      <!--email-->
       <div class="-mx-3 md:flex">
      <div>
        <label for="email" class="mt-2 after:content-['*'] after:ml-0.5 after:text-red-700 block text-lg  text-slate-700 font-bold">Email</label>
        <input type="email" name="email" id="email" placeholder="you@example.com" required="" class="mt-2 px-3 py-2 bg-white rounded-md border  border-slate-500  ml-2 " >
      </div>

      <!--phone number-->
      <div class="md:w-1/2">
        <label for="phone" class="mt-2 after:content-['*'] after:ml-0.5 after:text-red-700 block text-lg  text-slate-700 font-bold">Phone</label>
        <input type="text" name="phone"  id="phone"  placeholder="###-###-####" required="" class="mt-2 px-3 py-2 bg-white rounded-md border  border-slate-500  ml-2 " >
      </div>
      </div>

      <!--subject-->
        <div class="-mx-3 md:flex">
         <div class="md:w-full">
        <label for="subject" class="mt-2 after:content-['*'] after:ml-0.5 after:text-red-700 block text-lg  text-slate-700 font-bold">Subject</label>
        <input type="subject" name="subject" id="subject"  required="" class="sm:w-11/12 md:w-full mt-2 px-3 py-2 bg-white rounded-md border  border-slate-500  ml-2 " >
      </div>
        </div>
       
      <!--message-->
      <div class="-mx-3 md:flex">
      <div class="md:w-full">
      <label for="message" class="mt-2 after:content-['*'] after:ml-0.5 after:text-red-700 block text-lg  text-slate-700 font-bold">Message</label>
      <textarea type="message" name="message" id="message" rows="4" cols="20"  required="" class="sm:w-11/12 md:w-full mt-2 px-3 py-2 bg-white border rounded-md border-slate-500 ml-2 " > 
      </textarea>
      </div>
      </div>
      <!--button-->
      <div class="-mx-3 md:flex mt-2">
          <div class="md:w-full px-3">
      <button  type="submit" id="submit" class="md:w-full mt-10 bg-black text-white p-2 text-2xl rounded-md"><a href="thanks">Submit</a></button>
          </div>
      </div>
    </fieldset>
  </form>
  </section>
</main>
<TheFooter />
</div>
</template>

<script setup>


</script>
