<template>
<div>
<TheHeader />
<main>
    <div class="text-center mt-4">
    <h1 class="font-serif text-4xl">Contact</h1>
    <div class="text-lg">
    <p>Have a question?</p>
    <p>Thinking about booking a session?</p>
    <p>Please do not hesitate to reach out for any reason -- email, call, text, or just fill out the form below and hit "submit".</p>
    </div>
    </div>
    <!--form-->
  <form action="#"
  method="POST" class="flex justify-center mt-10">
    <fieldset>
        <!--first name-->
      <div>
        <label for="user" class="after:content-['*'] after:ml-0.5 after:text-red-700 block text-sm  text-slate-700 font-bold">First Name</label>
        <input type="text" name="user" id="user" placeholder="required" required class=" px-3 py-2 bg-white rounded-md border  border-slate-300  ml-2" >
      </div>
      <!--last name-->
      <div>
        <label for="user" class="mt-2 after:content-['*'] after:ml-0.5 after:text-red-700 block text-sm  text-slate-700 font-bold">Last Name</label>
        <input type="text" name="lastname" id="lastname" placeholder="required" required class="mt-2 px-3 py-2 bg-white rounded-md border border-slate-300  ml-2 " >
      </div>
      <!--email-->
      <div>
        <label for="email" class="mt-2 after:content-['*'] after:ml-0.5 after:text-red-700 block text-sm  text-slate-700 font-bold">Email</label>
        <input type="email" name="email" id="email" placeholder="optional" optional class="mt-2 px-3 py-2 bg-white rounded-md border  border-slate-300  ml-2 " >
      </div>
      <!--phone number-->
      <div>
        <label for="tel" class="mt-2 after:content-['*'] after:ml-0.5 after:text-red-700 block text-sm  text-slate-700 font-bold">Phone</label>
        <input type="tel" name="tel" id="tel" placeholder="required" required class="mt-2 px-3 py-2 bg-white rounded-md border  border-slate-300  ml-2 " >
      </div>
      <!--subject-->
      <div>
        <label for="subject" class="mt-2 after:content-['*'] after:ml-0.5 after:text-red-700 block text-sm  text-slate-700 font-bold">Subject</label>
        <textarea type="subject" name="subject" id="subject" placeholder="required" required class="mt-2 px-3 py-2 bg-white rounded-sm border  border-slate-300  ml-2 " ></textarea>
      </div>
      <!--message-->
      <div>
      <label for="message" class="mt-2 block text-sm  text-slate-700 font-bold">Message</label>
      <textarea type="message" name="message" id="message" rows="4" cols="20" placeholder="optional" optional class="mt-2 px-3 py-2 bg-white border rounded-sm border-slate-300  ml-2 " > 
      </textarea>
      </div>
      <!--button-->
      <button type="submit" class="mt-10 bg-black text-white p-2 text-2xl rounded-md">Submit</button>

    </fieldset>
  </form>
</main>
<TheFooter />
</div>
</template>

<script setup>
</script>
