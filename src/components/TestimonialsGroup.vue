<template>
  <div
    class="container mx-auto xl:max-w-[1110px] grid gap-x-[1.875rem] gap-y-6 xl:grid-cols-4 grid-cols-1 font-barlow"
  >
    <testimonial
      bg-color="#733FC8"
      border-color="#A775F1"
      title-color="#fff"
      name="Daniel Clifford"
      identity="Verified Graduate"
      main-comment="I received a job offer mid-course, and the subjects I learned
				were current, if not more so, in the company I joined. I
				honestly feel I got every penny’s worth."
      main-comment-color="#fff"
      sub-comment="“ I was an EMT for many years before I joined the bootcamp. I’ve been looking to make a transition and have heard some people who
				had an amazing experience here. I signed up for the free intro
				course and found it incredibly fun! I enrolled shortly
				thereafter. The next 12 weeks was the best - and most grueling -
				time of my life. Since completing the course, I’ve successfully
				switched careers, working as a Software Engineer at a VR
				startup. ”"
      sub-comment-color="#CFCFCF"
      img-url="/images/image-daniel.jpg"
      class="xl:col-span-2"
    >
      <img
        src="/images/bg-pattern-quotation.svg"
        class="absolute top-0 xl:right-[5rem] z-1 right-[1.5rem]"
        alt=""
      />
    </testimonial>

    <testimonial
      bg-color="#48556A"
      border-color="transparent"
      title-color="#fff"
      name="Jonathan Walters"
      identity="Verified Graduate"
      main-comment="The team was very supportive and kept me motivated"
      main-comment-color="#fff"
      sub-comment="“ I started as a total newbie with virtually no coding skills. I now work as a mobile engineer for a big company. This was one of the best investments I’ve made in myself. “"
      sub-comment-color="#fff"
      img-url="/images/image-jonathan.jpg"
      class="xl:col-span-1"
    >
    </testimonial>

    <testimonial
      bg-color="#fff"
      border-color="transparent"
      title-color="#48556A"
      name="Kira Whittle"
      identity="Verified Graduate"
      main-comment="Such a life-changing experience. Highly recommended!"
      main-comment-color="#48556A"
      sub-comment="“ Before joining the bootcamp, I’ve never written a line of code. I needed some structure from professionals who can help me learn programming step by step. I was encouraged to enroll by a former student of theirs who can only say wonderful things about the program. The entire curriculum and staff did not disappoint. They were very hands-on and I never had to wait long for assistance. The agile team project, in particular, was outstanding. It took my learning to the next level in a way that no tutorial could ever have. In fact, I’ve often referred to it during interviews as an example of my developent experience. It certainly helped me land a job as a full-stack developer after receiving multiple offers. 100% recommend!  ”"
      sub-comment-color="#48556A"
      img-url="/images/image-kira.jpg"
      class="xl:col-span-1 xl:col-start-4 xl:col-end-5 xl:row-start-1 xl:row-end-3"
    >
    </testimonial>

    <testimonial
      bg-color="#fff"
      border-color="transparent"
      title-color="#48556A"
      name="Jeanette Harmon"
      identity="Verified Graduate"
      main-comment="An overall wonderful and rewarding experience"
      main-comment-color="#48556A"
      sub-comment="“ Thank you for the wonderful experience! I now have a job I really enjoy, and make a good living while doing something I love. ”"
      sub-comment-color="#48556A"
      img-url="/images/image-jeanette.jpg"
      class="xl:col-span-1 pb-[26px]"
    >
    </testimonial>

    <testimonial
      bg-color="#19202D"
      border-color="#733FC8"
      title-color="#fff"
      name="Patrick Abrams"
      identity="Verified Graduate"
      main-comment="Awesome teaching support from TAs who did the bootcamp themselves. Getting guidance from them and learning from their experiences was easy."
      main-comment-color="#ECF2F8"
      sub-comment="“ The staff seem genuinely concerned about my progress which I find really refreshing. The program gave me the confidence necessary to be able to go out in the world and present myself as a capable junior developer. The standard is above the rest. You will get the personal attention you need from an incredible community of smart and amazing people.  ”"
      sub-comment-color="#fff"
      img-url="/images/image-patrick.jpg"
      class="xl:col-span-2 pb-[26px]"
    >
    </testimonial>
  </div>
</template>

<script setup>
import Testimonial from '@/components/Testimonial.vue'
</script>
