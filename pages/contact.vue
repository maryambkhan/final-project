<template>
<div>
<TheHeader />
<main>
    <div class="text-center mt-4">
    <h1 class="sm:text-lg font-serif md:text-4xl  lg:text-4xl mb-4">Contact</h1>
    <div class="sm:text-sm md:text-lg">
    <p>Have a question?</p>
    <p>Thinking about booking a session?</p>
    <p>Please do not hesitate to reach out if you have any questions.</p>
    </div>
    </div>
    <!--form-->
     <section class="mx-auto mt-2 bg-gray-300 max-w-6xl py-20 px-12 lg:px-24">
  <form action="#"
  method="POST" class="flex justify-center  mt-10">
    <fieldset>
        <!--first name-->
        <div class="flex gap-2">
      <div>
        <label for="user" class="after:content-['*'] after:ml-0.5 after:text-red-700 block text-lg  text-slate-700 font-bold">First Name</label>
        <input type="text" name="user" id="user"  class="mt-2 px-3 py-2 bg-white rounded-md border  border-slate-500  ml-2" >
      </div>
      <!--last name-->
      <div>
        <label for="user" class=" after:content-['*'] after:ml-0.5 after:text-red-700 block text-lg  text-slate-700 font-bold">Last Name</label>
        <input type="text" name="lastname" id="lastname"  class="mt-2 px-3 py-2 bg-white rounded-md border border-slate-500  ml-2 " >
      </div>
        </div>
      <!--email-->
      <div class="flex gap-2">
      <div>
        <label for="email" class="mt-2 after:content-['*'] after:ml-0.5 after:text-red-700 block text-lg  text-slate-700 font-bold">Email</label>
        <input type="email" name="email" id="email" placeholder="you@example.com" class="mt-2 px-3 py-2 bg-white rounded-md border  border-slate-500  ml-2 " >
      </div>
      <!--phone number-->
      <div>
        <label for="tel" class="mt-2 after:content-['*'] after:ml-0.5 after:text-red-700 block text-lg  text-slate-700 font-bold">Phone</label>
        <input type="number" name="number"  id="tel"  class="mt-2 px-3 py-2 bg-white rounded-md border  border-slate-500  ml-2 " >
      </div>
      </div>
      <!--subject-->
      <div>
        <label for="subject" class="mt-2 after:content-['*'] after:ml-0.5 after:text-red-700 block text-lg  text-slate-700 font-bold">Subject</label>
        <input type="subject" name="subject" id="subject"  class="w-full mt-2 px-3 py-2 bg-white rounded-md border  border-slate-500  ml-2 " >
      </div>
      <!--message-->
      <div>
      <label for="message" class="mt-2 block text-lg  text-slate-700 font-bold">Message</label>
      <textarea type="message" name="message" id="message" rows="4" cols="20"  class="w-full mt-2 px-3 py-2 bg-white border rounded-md border-slate-500  ml-2 " > 
      </textarea>
      </div>
      <!--button-->
      <button type="submit" class="w-full mt-10 bg-black text-white p-2 text-2xl rounded-md">Submit</button>
    </fieldset>
  </form>
    </section>
</main>
<TheFooter />
</div>
</template>

<script setup>
</script>
