<script lang="ts">
  import { base } from '$app/paths';
  import Navbar from "../../lib/components/Navbar.svelte";
  import EventCard from "../../lib/components/EventCard.svelte";
</script>

<title>Reagan HS Computer Science Club</title>
<meta name='description' content='The home page for the Ronald Reagan High School Computer Science club. We are a club for creative coding and Computer Science exploration. Join us to gain practical experience in Computer Science while having tons of fun!'/>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<div class="bg-teal-900 flex flex-col justify-center items-center w-full font-mono">
  <Navbar {base} />
  <h1 class='my-4 text-center text-4xl sm:text-5xl lg:text-7xl text-white'>Events</h1>
  <div class="flex flex-wrap justify-center w-full px-4">
    <EventCard name="General Meeting" date="October 23 after school" loc="RI244" desc="Join us for our second meeting of the year! We'll have snacks and a Halloween themed workshop." />
  </div>
</div>
<div class="h-[50vh] lg:h-[90vh] bg-teal-900"></div>
