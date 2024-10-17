<script lang="ts">
  import { base } from '$app/paths';
  import Navbar from "../../lib/components/Navbar.svelte";
  import FameCard from "../../lib/components/FameCard.svelte";
</script>

<title>Reagan HS Computer Science Club</title>
<meta name='description' content='The home page for the Ronald Reagan High School Computer Science club. We are a club for creative coding and Computer Science exploration. Join us to gain practical experience in Computer Science while having tons of fun!'/>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<div class="bg-teal-900 flex flex-col justify-center items-center w-full font-mono">
  <Navbar {base} />
  <h1 class='my-4 text-center text-4xl sm:text-5xl lg:text-7xl text-white'>Wall of Fame</h1>
  <div class="flex flex-wrap justify-center w-full px-4">
    <FameCard 
      authorName="William Liu" 
      projName="Reagan CS Club Website" 
      desc="The website of the Reagan High School Computer Science Club!" 
      link="https://renaissancedog.github.io/rrcsclub/" 
    />
    <FameCard 
      authorName="Sarthak Dayal" 
      projName="Former Reagan CS Club Website" 
      desc="The former website of the Club." 
      link="https://rr.hackclub.com/" 
    />
  </div>
</div>

<div class="h-[50vh] lg:h-[90vh] bg-teal-900"></div>
