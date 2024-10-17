<script>
  export let name, role, desc, img;
</script>

<section class="flex flex-col lg:flex-row items-center justify-around w-full p-4 font-mono">
  <div class="bg-white my-4 text-center rounded-xl shadow-md w-full lg:w-1/2">
    <h2 class='px-4 py-2 text-2xl lg:text-3xl text-white bg-teal-700 rounded-t-xl'>{name}</h2>
    <h2 class='px-4 py-2 text-xl lg:text-2xl text-white bg-teal-700'>{role}</h2>
    <div class="flex flex-row">
      <img src={img} alt={name} height=100 width=100>
      <p class='m-4 text-lg lg:text-2xl'>{desc}</p>
    </div>
  </div>
</section>