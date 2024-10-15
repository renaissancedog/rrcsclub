<script>
  export let authorName, projName, desc, link;
</script>

<section class="flex flex-col lg:flex-row items-center justify-around w-full p-4">
  <div class="bg-white font-sans my-4 text-center rounded-xl shadow-md w-full lg:w-1/2">
    <h2 class='px-4 py-2 text-2xl lg:text-3xl text-white bg-teal-700 rounded-t-xl'>{projName}</h2>
    <h2 class='px-4 py-2 text-xl lg:text-2xl text-white bg-teal-700'>{authorName}</h2>
    <p class='m-4 text-lg lg:text-2xl'>{desc} <br> 
      <a class="break-words underline text-blue-600" target="_blank" rel="noopener noreferrer" href={link}>{link}</a>
    </p>
  </div>
</section>