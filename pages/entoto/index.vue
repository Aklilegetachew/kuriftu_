<template>
  <div>
    <HeaderApp />
    <Destinav base="entoto/" home="entoto/" dir="Entoto" />
    <Dindex :index="index" />
  </div>
</template>

<script>
import Destinav from "../../components/Destinav.vue";
export default {
  components: { Destinav },
  data() {
    return {
      index: {
        // heroImg: "awash/awash-cover.webp",
        video: "705084951",

        bishTitle: {
          subTitle: "ENTOTO PARK, ADDIS ABABA",
          title: "kuriftu resort & spa Entoto",
          text: `Kuriftu Entoto Adventure Park offers an off the beaten path experience in the heart of the Entoto Mountain. With an abundance of eucalyptus trees, this dense forest is considered to be the lungs of Addis Ababa with significant cultural and historical relevance. Telling the story of the founding of Addis Ababa from the time of Emperor Menelik II.
The Adventure Park captures the beauty of this sacred location by highlighting nature based adventure tourism activites that allow families and tourists alike to emmerse themselves within this ecosystem. From activities ranging from rock-climbing to horse back riding and seculded glamping accommodations, this destination is truly one of a kind!`,
        },
        // slides
        photos: [
          "Entoto/slide1.webp",
          "Entoto/slide2.2.webp",
          "Entoto/slide2.webp",
          "Entoto/slide3.webp",
          "Entoto/slide4.webp",
          "Entoto/slide5.webp",
          "Entoto/slide6.webp",
        ],

        // acc cover image
        accImg: "Entoto/Accomodation.webp",
        // acc content
        accTitle: {
          subTitle: "ACCOMODATION",
          title: "Glamping",
          text: `With a backdrop of the distinct wild and lush Entoto Forest, our Kuriftu Entoto Adventure Park offers an alternative hospitality experience. With locally sourced materials used to construct and furnish our Presidential Cabin and the interior of our Glamping facilties, guests are placed in a natural setting to simply relax and savour the peace and quiet.`,
          link: "view all accomodations",
          url: "entoto/acc",
        },

        // destination highlight section
        highlight: [
          {
            id: 1,
            img: "Entoto/AdventureLong.webp",
            subTitle: "Experience",
            title: "Adventure",
            text: `The Kuriftu Entoto Adventure Park has become the heart and soul of Entoto Mountain, providing a bundle of activities found no where else in the country! Targeting adrenaline junkies to families looking for an exciting getaway - come on join us for an unforgettable experience!`,
            uri: "#",
            url: "Explore",
          },
          {
            id: 2,
            img: "Entoto/mountain.webp",
            subTitle: "dining",
            title: "Mountain Dining",
            text: `Our Adventure Park includes 5 dining hot spots, ranging from 5-star international standard cuisine, to cultural dishes craved by all!
Each restaurant is strategically placed in key activity based areas, like our Horse Ranch, Rope Course and Go Karting station, that allow guests a truly emmersive experience! `,
            uri: "#",
            url: "Explore",
          },
          {
            id: 3,
            img: "Entoto/wellness.webp",
            subTitle: "wellness",
            title: "Forest Spa",
            text: `Take a moment to inhale the fresh air and aromatic scent from the eucalyptus forest by allowing your mind, body and soul to experience the calm energy provided by the natural elements surrounding the park. Our goal is to facilitate a scerene envirnoment within our unique spa aesthetic, catering to those seeking to reconnect with mother earth.`,
            uri: "#",
            url: "Explore",
          },
          {
            id: 4,
            img: "Entoto/corporate.webp",
            subTitle: "CORPORATE EXPERIENCE",
            title: "Corporate Teams",
            text: `We strive to create a safe haven for corporate teams to liberate themseves of the hustle and bustle of daily work life. With custom packages based on the wants and needs of our guests, Kuriftu Entoto Adventure Park guarantees a space for teams to work together to stregthen relationships and wind down as a collective. This sense of relaxation has proven to rejuvinate individuals and inspire stronger work efforts upon their return to reality.`,
            uri: "#",
            url: "Explore",
          },
          {
            id: 5,
            img: "Entoto/celebration.webp",
            subTitle: "Celebration",
            title: "A memorabile experience",
            text: `Allow us to share your greatest moments by curating unforgettable celebratory events! Whether it be a birthday party in the Trampoline World for kids, a relaxing friends night out in our Hammok Village, wedding or custom event in the Entoto Peak Restaurant and outdoor space - We've got you covered!`,
            uri: "#",
            url: "Explore",
          },
          {
            id: 6,
            img: "Entoto/slide6.webp",
            subTitle: "PACKAGE OFFERS",
            title: "Future travels",
            text: `Treat someone to a world full of incredible experiences - From an adventure in the heart of Entoto Mountain, to a quiet relaxing dinner by the lake side in Debre Zeit, Kuriftu Gift Vouchers are the perfect gifts for yourself, a friend, a co-worker or a loved one!`,
            uri: "#",
            url: "Explore",
          },
        ],
        // map section
        mapInfo: `14.9 km from Addis Ababa Bole International Airport Entoto Park, Ethiopia`,
        iframe: `https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d44577.49805641681!2d38.736620781160575!3d9.051777430683375!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x164b8f84811f84a1%3A0x336681194adaaef!2sKuriftu%20Restaurant%20in%20Entoto%20Park!5e0!3m2!1sen!2sus!4v1655482874195!5m2!1sen!2sus`,
      },
    };
  },
};
</script>

<style>
</style>
