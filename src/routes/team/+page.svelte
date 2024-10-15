<script lang="ts">
  import { base } from '$app/paths';
  import Navbar from "../../lib/components/Navbar.svelte";
  import OfficerCard from "../../lib/components/OfficerCard.svelte";
</script>

<title>Reagan HS Computer Science Club</title>
<meta name='description' content='The home page for the Ronald Reagan High School Computer Science club. We are a club for creative coding and Computer Science exploration. Join us to gain practical experience in Computer Science while having tons of fun!'/>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<div class="bg-teal-900 flex flex-col justify-center items-center w-full">
  <Navbar {base} />
  <h1 class='my-4 text-center text-4xl sm:text-5xl lg:text-7xl text-white'>Our Team</h1>
  <p class="text-xl text-white text-center">Meet the folks responsible for running the club!</p>
  <div class="flex flex-wrap justify-center w-full px-4">
    <OfficerCard name="Alexis Tao" role="President" desc="Lorem ipsum dolor sit amet" img=""/>
    <OfficerCard name="William Liu" role="Webmaster" desc="Hi! I made this website." img="william.png"/>
  </div>
</div>
<div class="h-[50vh] lg:h-[90vh] bg-teal-900"></div>
