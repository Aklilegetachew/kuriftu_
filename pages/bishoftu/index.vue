<template>
  <div>
    <HeaderApp />
    <Destinav base="bishoftu/" home="bishoftu/" dir="Bishoftu" />
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
        // heroImg: "bishoftu/LakeView.webp",
        video: "705340877",
        bishTitle: {
          subTitle: "Lake kuriftu, bishoftu",
          title: "kuriftu resort & spa bishoftu",
          text: `Located on the northen tip of Bishoftu encompassing the smallest of the four lakes lies our flagship resort, Kuriftu Resort & Spa Bishoftu. Born from Mr. Tadiwos's vision to create luxury resort destinations in neighboring cities of the capital, this resort made its mark in 2007 as the first 5-star resort in the country. Kuriftu has redefined the meaning of service in Ethiopia, with an outstanding track record and dedicated loyalty program that keeps our guests more than satisfied, Kuriftu Bishoftu is a home away from home`,
        },
        // slides
        photos: [
          "bishoftu/firstSlider/1.webp",
          "bishoftu/firstSlider/2.webp",
          "bishoftu/acc/loft/3.webp",
          "long.webp",
          "bishoftu/dining/KuriftuBuffetO.webp",
          "bishoftu/ExpLong.webp",
          "bishoftu/acc/pre8.webp",
        ],

        // acc cover image
        accImg: "bishoftu/bishAcc.webp",
        // acc content
        accTitle: {
          subTitle: "ACCOMODATION",
          title: "Surrounded by Nature",
          text: `With 150 rooms spread across the resort grounds, we offer a range of views and amenties that showcase our brands authentic design and incredible beauty `,
          link: "view all accomodations",
          url: "bishoftu/acc",
        },

        // destination highlight section
        highlight: [
          {
            id: 1,
            img: "bishoftu/ExpLong.webp",
            subTitle: "Experience",
            title: "Adventure",
            text: `Discover the hidden gems of Kuriftu Bishoftu from bird watching and kayaking on the lake, to a wild adventure in our Waterpark and Circus performances `,
            uri: "bishoftu/exp",
            url: "Explore",
          },
          {
            id: 2,
            img: "bishoftu/DiningLong.webp",
            subTitle: "dining",
            title: "culinary on the lake",
            text: `Enjoy the various traditional and western cuisines carefully prepared for your satisfaction while taking in the beautiful scenery`,
            uri: "bishoftu/dining",
            url: "Explore",
          },
          {
            id: 3,
            img: "bishoftu/wellLong.webp",
            subTitle: "wellness",
            title: "Rejuvination",
            text: `Absorb the peaceful energy that floods this environment, allowing our guests to embrace their natural surrounds with an open and relaxed mind. Whether it be a family visit, business trip or romantic getaway, Kuriftu Bishoftu has a way of making each stay special `,
            uri: "bishoftu/well",
            url: "Explore",
          },
          {
            id: 4,
            img: "Entoto/corporate.webp",
            subTitle: "corporate",
            title: "CORPORATE EXPERIENCE",
            text: `Allow us to share your greatest moments by curating unforgettable celebratory events! Whether it be a birthday party in the Waterpark for kids, a pool party by The Village Pool & Bar, or a one of a kind nature based wedding that can accommodate up to 3,000 people - We've got you covered!`,
            uri: "bishoftu/corp",
            url: "Explore",
          },
          {
            id: 5,
            img: "bishoftu/celeLong.webp",
            subTitle: "Celebration",
            title: "A memorabile experience",
            text: `Allow us to share your greatest moments by curating unforgettable celebratory events! Whether it be a birthday party in the Waterpark for kids, a pool party by The Village Pool & Bar, or a one of a kind nature based wedding that can accommodate up to 3,000 people - We've got you covered!`,
            uri: "bishoftu/event",
            url: "Explore",
          },
          {
            id: 6,
            img: "long.webp",
            subTitle: "gift voucher",
            title: "future travels",
            text: `Gift a friend or loved to an unforgettable stay at our flagship resort with guaranteed excellence in service, cuisine, and fun!`,
            uri: "bishoftu/gift",
            url: "Explore",
          },
        ],
        // map section
        mapInfo: `53.8 km from Addis Ababa Bole International Airport Lake Bishoftu, Ethiopia`,
        iframe: `https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3943.061646113906!2d39.00067561533771!3d8.780270895251148!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x164b0cba1728a73d%3A0x44f92b98676731e7!2sKuriftu%20Resort%20%26%20Spa%20Bishoftu!5e0!3m2!1sen!2sus!4v1655475159460!5m2!1sen!2sus`,
      },
    };
  },
};
</script>

<style>
</style>
