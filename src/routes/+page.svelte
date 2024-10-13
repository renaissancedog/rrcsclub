<script lang="ts">
  import { base } from '$app/paths';
  import Navbar from "../lib/components/Navbar.svelte";
  const apply_link = "https://forms.gle/i3ncV7JumfaodDXK8";
  const contact_link = "https://forms.gle/QkcoFtm9A6woxrs28";
  const constitution_link = "https://github.com/RR-CS-Club/Club-Constitution";
</script>

<html lang="en">
<!-- <script defer data-domain="rrcsclub.vercel.app" src="https://plausible.io/js/plausible.js"></script> -->
<title>Reagan HS Computer Science Club</title>
<meta name='description' content='The home page for the Ronald Reagan High School Computer Science club. We are a club for creative coding and Computer Science exploration. Join us to gain practical experience in Computer Science while having tons of fun!'/>
<div class="bg-white flex flex-col justify-center items-center w-screen">
  <Navbar {base}/>
  <section class="h-[70rem] bg-cover bg-[url('/TopBg.svg')] flex flex-col text-center items-center justify-center w-screen bg-no-repeat">
    <h1 class="text-7xl h-32 pb-16 text-blue-800 uppercase flex flex-col top-0 justify-center"> Reagan CS Club </h1>
    <div class="text-4xl leading-normal text-gray-800">
      The club for <span class="rounded-lg text-pink-700 bg-pink-200 font-bold">creative coding,</span>
      <span class="rounded-lg text-orange-500 bg-yellow-200 font-bold">collaboration
      </span>
      and
      <span class="rounded-lg text-blue-600 bg-green-200 font-bold">
        project-led learning
      </span>.
      <div class="text-xl flex flex-col sm:flex-row items-center justify-center">
        <div class="flex justify-center items-center h-28 w-full sm:w-60 my-4 sm:my-8 mx-4 sm:mx-12 rounded-lg cursor-pointer text-white text-center bg-gray-800 bg-contain bg-no-repeat">
          <a href={apply_link} class="text-3xl text-center">APPLY</a>
        </div>
        <div class="flex justify-center items-center h-28 w-full sm:w-60 my-4 sm:my-8 mx-4 sm:mx-12 rounded-lg cursor-pointer text-white text-center bg-gray-800 bg-contain bg-no-repeat">
          <a href={contact_link} class="text-3xl text-center">CONTACT</a>
        </div>
      </div>
    </section>
    <main class="bg-teal-900 w-screen flex flex-col justify-center items-center">
      <section class="flex flex-col items-center justify-center">
        <h1 class="rounded-2xl m-12 p-6 text-4xl text-teal-300 uppercase font-black bg-blue-700">Who We Are</h1>
        <p class="m-12 w-fit text-3xl text-white font-light">
          We are a passionate community of coders, designers and explorers
          who like to learn by doing. The core philosophy of this club is
          building fun, real-world projects to learn coding. Coding is a
          superpower and it shows that you do not need much to change the
          world — just a computer or even a phone and a creative mind. <br><br>
          Coding has become an essential skill for thousands of
          professions and technological literacy is absolutely necessary in
          today's world where technology is a key aspect of our everyday
          lives. We aim to bring this necessary technological literacy to
          everyone so that no one is left behind in this revolution.
        </p>
      </section>
      <h1 class="rounded-2xl m-12 p-6 text-4xl text-teal-300 uppercase font-black bg-blue-700">What we do</h1>
      <section class="px-4 items-center justify-center w-screen">
        <h1 class="text-white text-3xl text-center pb-8">Club Workshop Meetings</h1>
        <section class="flex flex-col md:flex-row items-center justify-around w-full">
          <div class="bg-white mt-2 rounded-xl w-full md:w-1/6">
            <h2 class='my-4 h-12 text-center text-3xl text-white bg-teal-700'>Initiation</h2>
            <p class='m-4 text-3xl'>
              The Club leader guides everyone through a new topic. Everyone writes some code and understands the basics of the topic.
            </p>
          </div>
          <div class="bg-white mt-2 rounded-xl w-full md:w-1/6">
            <h2 class='my-4 h-12 text-center text-3xl text-white bg-teal-700'>Creation</h2>
            <p class='m-4 text-3xl'>
              Everyone starts creating, in teams or on their own on a project of their choice. The club officers guide everyone through projects.
            </p>
          </div>
          <div class="bg-white mt-2 rounded-xl w-full md:w-1/6">
            <h2 class="my-4 h-12 text-center text-3xl text-white bg-teal-700">Demos</h2>
            <p class='m-4 text-3xl'>
              Anyone who wishes to can present what they built and inspire others to build similar fun projects.
            </p>
          </div>
        </section>
        <p class="text-3xl pt-8 text-white font-light text-center pb-4">
          Beginners are highly encouraged to attend these workshops to learn programming and new skills.
        </p>
      </section>
      <section class="drop-shadow-2xl flex flex-col items-center justify-center">
        <h1 class="rounded-2xl m-12 p-6 text-4xl text-teal-300 uppercase font-black bg-blue-700">Beyond Meetings</h1>
        <div class="mx-12 text-left w-fit text-3xl text-white font-light">
          <p> Our club goes beyond simple meetings and we host a ton of fun events. Some events we are planning for this year include:</p>
          <ul class="list-disc">
            <li>2-day Hackathons</li>
            <li>Hack Nights</li>
            <li>Coding Challenges</li>
            <li>Hour of Code</li>
            <li>TED Talks</li>
            <li>Programming Competitions</li>
          </ul>
          <p class="py-4">For more information on upcoming events, check out the <a class="underline" href="{base}/events">EVENTS</a> page.</p>
        </div>
      </section>
      <section class="drop-shadow-2xl flex flex-col items-center justify-center">
        <h1 class="rounded-2xl m-12 p-6 text-4xl text-teal-300 uppercase font-black bg-blue-700">Requirements</h1>
        <p class="m-12 w-fit text-3xl text-white font-light">
          In order to be eligible to join Reagan CS Club, you must be a
          student of Ronald Reagan High School in San Antonio, Texas and be
          in good standing with NEISD policies and government laws. Those
          are the only requirements for joining as a new member.<br><br>
          In order to maintain or renew membership, there is one
          additional requirement other than the ones mentioned above. You
          must attend 3 events or workshops held or approved by Reagan Hack
          Club every school semester. More information is in the club
          <a class="underline" href="{constitution_link}">constitution</a>. If you meet the requirements,
          <a class="underline" href="{apply_link}">apply</a>
          now to be a part of the club!
        </p>
      </section>
    </main>
    </html>
    