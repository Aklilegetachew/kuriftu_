<template>
  <div>
    <section class="footer">
      <div class="container">
        <div class="member-cta">
          <h1 class="title">become a member</h1>
          <p class="text">
            To recieve updates about exclusive experience and our newsletter,
            please register
          </p>
          <div class="btn-container">
            <nuxt-link to="#" class="btn-cta"> Sign Up </nuxt-link>
          </div>
        </div>
        <div class="lower">
          <div class="more-info">
            <h1 class="title">More Information</h1>
            <ul>
              <li>
                <nuxt-link to="#">About Us</nuxt-link>
              </li>
              <li>
                <nuxt-link to="#">Contact Us</nuxt-link>
              </li>
              <li>
                <nuxt-link to="#">Gift Card</nuxt-link>
              </li>
              <li>
                <nuxt-link to="#">Upcoming Projects</nuxt-link>
              </li>
              <li>
                <nuxt-link to="#">Careers</nuxt-link>
              </li>
              <li>
                <nuxt-link to="#">Privacy</nuxt-link>
              </li>
              <li>
                <nuxt-link to="#">Legal Notice</nuxt-link>
              </li>
              <li>
                <nuxt-link to="#">Articles</nuxt-link>
              </li>
              <li>
                <nuxt-link to="#">News Letters</nuxt-link>
              </li>
              <li>
                <nuxt-link to="#">Gallery</nuxt-link>
              </li>
            </ul>
          </div>

          <div class="resorts">
            <h1 class="title">Resorts</h1>
            <ul>
              <li>
                <nuxt-link to="#">Bishoftu</nuxt-link>
              </li>
              <li>
                <nuxt-link to="#">Entoto</nuxt-link>
              </li>
              <li>
                <nuxt-link to="#">Lake Tana</nuxt-link>
              </li>
              <li>
                <nuxt-link to="#">Awash</nuxt-link>
              </li>
              <li>
                <nuxt-link to="#">Afar</nuxt-link>
              </li>
            </ul>
          </div>

          <div class="wellness">
            <h1 class="title">wellness</h1>
            <ul>
              <li>
                <nuxt-link to="#">Boston</nuxt-link>
              </li>
              <li>
                <nuxt-link to="#">Entoto</nuxt-link>
              </li>
            </ul>
          </div>

          <div class="adv">
            <h1 class="title">Adventure</h1>
            <ul>
              <li>
                <nuxt-link to="#">Waterpark</nuxt-link>
              </li>
              <li>
                <nuxt-link to="#">Entoto</nuxt-link>
              </li>
            </ul>
          </div>
        </div>

        <div class="socials">
          <h1 class="title">socials</h1>

          <div class="icons">
            <img src="@/assets/img/icons/fb.svg" alt="" />
            <img src="@/assets/img/icons/instagram.svg" alt="" />
            <img src="@/assets/img/icons/twitter.svg" alt="" />
            <img src="@/assets/img/icons/youtube.svg" alt="" />
            <img src="@/assets/img/icons/linkedin.svg" alt="" />
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.footer {
  margin-top: 2.14rem;
  margin-bottom: 1.5rem;
  .container {
    .member-cta {
      h1,
      p,
      a {
        margin-bottom: 1.4rem;
      }
    }
    .lower {
      div {
        margin-top: 1.5rem;
      }
      h1 {
        margin-bottom: 0.9rem;
        text-decoration: underline;
      }
      ul {
        display: grid;
        grid-template-columns: 1fr 1fr;
        li {
          margin-bottom: 0.6rem;
          a {
            font-family: "Neue Helvetica thin";
            font-weight: 800;
            letter-spacing: 0.07rem;
            font-size: 0.8rem;
            color: #808080;
          }
        }
      }
    }
    .socials {
      margin-top: 1.5rem;
      h1 {
        text-decoration: underline;
        margin-bottom: 0.9rem;
      }
      .icons {
        display: flex;
        gap: 1.5rem;
      }
    }
  }
}

@include responsive($md) {
  .footer {
    .container {
      .member-cta {
        display: grid;
        grid-template-columns: 1fr 1fr 1fr 1fr;
        grid-template-areas: "title text text btn";
        h1 {
          grid-area: title;
        }
        p {
          grid-area: text;
        }
        .btn-container {
          grid-area: btn;
        }
      }
      .lower {
        display: grid;
        grid-template-columns: 1fr 1fr;
        grid-template-areas:
          "info resorts"
          "wellness adv";
        .more-info {
          grid-area: info;
        }
        .resorts {
          grid-area: resorts;
        }
        .wellness {
          grid-area: wellness;
        }
        .adv {
          grid-area: adv;
        }
        div {
          margin-top: 1.5rem;
        }
        ul {
          display: grid;
          grid-template-columns: 1fr;
        }
      }
    }
  }
}

@include responsive($lg) {
  .footer {
    .container {
      display: grid;
      grid-template-columns: 1fr 1fr 1fr;
      grid-template-rows: 1fr;
      grid-template-areas:
        "member member member"
        "lower  lower  socials";
      .member-cta {
        grid-area: member;
        grid-template-columns: 1fr 1fr 1fr 1.5rem 1fr;
        grid-template-areas: "title text text . btn";
        margin-bottom: 4.125rem;
        h1 {
          grid-area: title;
        }
        p {
          grid-area: text;
        }
        .btn-container {
          grid-area: btn;
        }
      }
      .lower {
        grid-area: lower;
        display: grid;
        text-align: center;
        grid-template-columns: 1fr 1fr;
        grid-template-areas:
          "info resorts"
          "info wellness"
          "info adv"
          "info .";
        div {
          margin-top: 1.5rem;
        }
        ul {
          display: grid;
          grid-template-columns: 1fr;
          text-align: center;
        }
      }
      .socials {
        grid-area: socials;
        justify-self: center;
        .icons {
          display: block;
          img {
            margin-bottom: 1.5rem;
          }
        }
      }
    }
  }
}
</style>
