<script>
  export let authorName, projName, desc, link;
</script>
<section class="flex flex-col lg:flex-row items-center justify-around w-full">
  <div class="bg-white font-sans my-2 text-center rounded-xl">
    <h2 class='px-2 mt-4 text-3xl text-white bg-teal-700'>{projName}</h2>
    <h2 class='px-2 mb-2 text-2xl text-white bg-teal-700'>Created by {authorName}</h2>
    <p class='m-4 text-3xl'>{desc} <br> <a class="underline" target="_blank" rel="noopener noreferrer"  href={link}>{link}</a></p>
  </div>
</section>