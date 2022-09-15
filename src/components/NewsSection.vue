<template>
  <!-- Section "Latest News" -->
  <section id="news">
    <div class="news container">
      <div class="news-top">
        <h3>Latest News</h3>
      </div>
      <div class="news-bottom">
        <!-- 3 cards -->
        <b-container class="bv-example-row">
          <div class="row">
            <b-row class="news-row" v-for="(card, i) in cards" :key="i">
              <b-card
                img-src="https://i.imgur.com/Zon1BzL.png"
                img-alt="Image"
                img-top
                tag="article"
                style="max-width: 20rem; min-height: 30rem"
                class="mb-2"
              >
                <div class="d-flex justify-content-between">
                  <div class="d-flex">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="16"
                      height="16"
                      fill="currentColor"
                      class="bi bi-person-fill"
                      viewBox="0 0 16 16"
                    >
                      <path
                        d="M3 14s-1 0-1-1 1-4 6-4 6 3 6 4-1 1-1 1H3zm5-6a3 3 0 1 0 0-6 3 3 0 0 0 0 6z"
                      />
                    </svg>
                    <p class="author">&ensp;Conrad Hegarty</p>
                  </div>
                  <div class="d-flex">
                    <svg
                      class="svg"
                      width="16"
                      height="16"
                      xmlns="http://www.w3.org/2000/svg"
                      viewBox="0 0 448 512"
                    >
                      <path
                        d="M128 0c17.7 0 32 14.3 32 32V64H288V32c0-17.7 14.3-32 32-32s32 14.3 32 32V64h48c26.5 0 48 21.5 48 48v48H0V112C0 85.5 21.5 64 48 64H96V32c0-17.7 14.3-32 32-32zM0 192H448V464c0 26.5-21.5 48-48 48H48c-26.5 0-48-21.5-48-48V192zm64 80v32c0 8.8 7.2 16 16 16h32c8.8 0 16-7.2 16-16V272c0-8.8-7.2-16-16-16H80c-8.8 0-16 7.2-16 16zm128 0v32c0 8.8 7.2 16 16 16h32c8.8 0 16-7.2 16-16V272c0-8.8-7.2-16-16-16H208c-8.8 0-16 7.2-16 16zm144-16c-8.8 0-16 7.2-16 16v32c0 8.8 7.2 16 16 16h32c8.8 0 16-7.2 16-16V272c0-8.8-7.2-16-16-16H336zM64 400v32c0 8.8 7.2 16 16 16h32c8.8 0 16-7.2 16-16V400c0-8.8-7.2-16-16-16H80c-8.8 0-16 7.2-16 16zm144-16c-8.8 0-16 7.2-16 16v32c0 8.8 7.2 16 16 16h32c8.8 0 16-7.2 16-16V400c0-8.8-7.2-16-16-16H208zm112 16v32c0 8.8 7.2 16 16 16h32c8.8 0 16-7.2 16-16V400c0-8.8-7.2-16-16-16H336c-8.8 0-16 7.2-16 16z"
                      />
                    </svg>
                    <p class="date">&ensp;26 June, 19</p>
                  </div>
                </div>
                <!-- Text -->
                <h6>Sometimes on purpose injecteded.</h6>
                <b-card-text class="card-text">
                  There are many variations of passages of Lorem Ipsum
                  available.
                </b-card-text>
                <b-link class="b-link" href="">Continue reading...</b-link>
                <!-- End Text -->
              </b-card>
            </b-row>
          </div>
        </b-container>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "NewsSection",
  data() {
    return {
      cards: ["", "", ""],
    };
  },
};
</script>

<style scoped>
#news .container {
  min-height: 40vh;
  width: 100%;
  display: flex;
  align-items: center;
}
.news-top h3 {
  color: rgba(50, 50, 50, 255);
  font-family: "Roboto Slab", serif;
  font-weight: bold;
  font-size: 35px;
  text-align: center;
  padding-top: 5rem;
  text-decoration-line: underline;
  text-decoration-style: solid;
  text-decoration-color: rgba(196, 234, 230, 255);
  text-decoration-thickness: 5px;
  text-decoration-skip-ink: none;
}
#news .news {
  flex-direction: column;
  max-width: 100vw;
  min-height: 80vh;
}
#news .news-row {
  margin: 2rem 1rem 0;
}
/* Card CSS */
#news .author,
.date {
  font-size: 10px;
  font-family: "PT Sans";
}
#news .date,
.svg {
  align-items: flex-end;
}
#news h6 {
  font-family: "Roboto Slab", serif;
  font-size: 17px;
  font-weight: 600;
  color: rgba(50, 50, 50, 255);
}
#news .card-text {
  margin-bottom: 2rem;
}
.b-link {
  color: rgba(112, 112, 112, 255);
}
.b-link:hover {
  text-decoration: none;
  color: rgba(0, 184, 148, 255) !important;
  font-weight: bold;
}
</style>
