<template>
  <div>
    <HeaderApp />
    <Destinav base="" home="/laketana" dir="Lake Tana" />
    <Gallery :gallery="gallery" />
    <BishFooter :footer="footer" />
  </div>
</template>

<script>
export default {
  data() {
    return {
      gallery: [
        {
          id: 1,
          src: "laketana/event/soci.webp",
        },
        {
          id: 2,
          src: "laketana/event/bd.webp",
        },
        {
          id: 3,
          src: "laketana/acc/gardenview/1.webp",
        },
        {
          id: 4,
          src: "laketana/exp/BirdWatching.webp",
        },
        {
          id: 5,
          src: "laketana/dining/3.webp",
        },
        {
          id: 6,
          src: "laketana/corp/ConferenceHall.webp",
        },
        {
          id: 7,
          src: "laketana/event/LakeSide.webp",
        },
        {
          id: 8,
          src: "laketana/event/Cabana.webp",
        },
        {
          id: 9,
          src: "laketana/exp/TripToTheFalls.webp",
        },
        {
          id: 10,
          src: "laketana/exp/CabanaDinig.webp",
        },
        {
          id: 11,
          src: "laketana/event/soci.webp",
        },
      ],
      footer: {
        title: "Kuriftu Resort & Spa Bishoftu",
        second: {
          first: "53.7 km from Addis Ababa Bole International Airport",
          second: "Lake Bishoftu",
          thrid: "Ethiopia",
        },
        thrid: {
          first: "Contact us on our direct phone line 9693",
          second: "Reception Desk +251924949494",
          thrid: "Email us at booking@kurifturesorts.com",
        },
        fourth: {
          url: "/",
        },
      },
    };
  },
};
</script>

<style>
</style>
