<template>
  <div>
    <HeaderApp />
    <Destinav base="" home="/entoto" dir="Entoto" />
    <Dining :dining="dining" />
    <BishFooter :footer="footer" />
  </div>
</template>

<script>
export default {
  data() {
    return {
      dining: {
        slides: [
          "Entoto/event/s2.webp",

          "Entoto/event/s4.webp",
          "Entoto/event/s5.webp",
          "Entoto/event/s7.webp",
          "Entoto/event/s6.webp",
        ],
        heroTitle: "Dinning at Kuriftu Entoto Adventure Park",
        heroSubTitle: "kuriftu resort & spa bishoftu dining",
        heroText: `Ethiopia's wide variety of culture results in an endless palate of flavors from around the world - our aim is to incorporate mixed cuisine from traditional injera to international dishes under the same roof! Built and designed by our crafty Kuriftu Woodwork team, each restaurant showcases our work in manipulation of natural materials such as wood, rope, stone, brick and bamboo.
`,
        feature: {
          img: "Entoto/din/EntotoPeakRestaurant.webp",
          title: "Entoto Peak Restaurant",
          text: `At the end of a long day of treking uphill lies our Mountain Peak Restaurant, a spacious dining hall with mixed cuisine and a variety of seating stations that overlook the incredible landscape. `,
          uri: "/",
          link: "view menu",
        },
        Lfeature: {
          img: "Entoto/din/TheRidersRanch.webp",
          title: "The Riders Ranch",
          text: `Enjoy our specialty Chekla Tibs while overlooking the horse stable and its track at The Riders Ranch.`,
          uri: "/",
          link: "view menu",
        },
        feature1: {
          img: "Entoto/din/CastelBar&Grill.webp",
          title: "Castel Bar & Grill",
          text: `Nestled in the forest you'll find our open air Castel Wine Bar & Grill with the Rope Course literally overhead, this experience is like no other! `,
          uri: "/",
          link: "view menu",
        },
        Lfeature1: {
          img: "Entoto/din/TheMarksmanBar&Grill.webp",
          title: "The Marksman Bar & Grill",
          text: `Didn't hit bullseye? No sweat, take a breather before your next round at The Marksman Bar & Grill for the best burgers and fries on this side of the mountain`,
          uri: "/",
          link: "view menu",
        },
        feature2: {
          img: "Entoto/din/PitStopBar&Grill.webp",
          title: "Pit Stop Bar & Grill / Refuel",
          text: `Wind down from the rush of competing against your friends at Pit Stop Bar & Grill, just make sure whoever came last treats the team for a beer `,
          uri: "/",
          link: "view menu",
        },
        other: [
          {
            img: "Entoto/din/FamilyDining.webp",
            title: "Family Dining ",
            text: `Enjoy a large family style dish at any of our restaurant locations - the more the merrier!`,
          },
          {
            img: "Entoto/din/ArcheryCallenge.webp",
            title: "Archery Challenge",
            text: `Think you can hit the target? Why not bet on it with a friend, loser buys the other lunch!`,
          },
        ],
      },
      footer: {
        title: "Kuriftu Resort & Spa Entoto",
        second: {
          first: "14.9 km from Addis Ababa Bole International Airport",
          second: "Entoto Park",
          thrid: "Ethiopia",
        },
        thrid: {
          first: "Contact us on our direct phone line 9693",
          second: "Reception Desk +251905061020",
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
