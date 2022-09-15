<template>
  <!-- Section "Software Skill" -->
  <section id="skill">
    <div class="skill container">
      <div class="skill-top">
        <h3>Software Skill</h3>
      </div>
      <div class="d-flex justify-content-center">
        <div class="row">
          <div class="col-12 col-md-6">
            <!--  Range Sliders -->
            <div class="skill-bar">
              <h6>Photoshop</h6>
              <ol class="skill-progress">
                <li class="skill-complete"><span>0%</span></li>
                <li class="skill-complete"><span>10%</span></li>
                <li class="skill-complete"><span>20%</span></li>
                <li class="skill-complete"><span>30%</span></li>
                <li class="skill-complete"><span>40%</span></li>
                <li class="skill-complete"><span>50%</span></li>
                <li class="skill-complete"><span>60%</span></li>
                <li class="skill-complete"><span>70%</span></li>
                <li class="skill-complete"><span>80%</span></li>
                <li class="skill-active"><span>92%</span></li>
                <li><span>95%</span></li>
                <li><span>100%</span></li>
              </ol>
            </div>
            <div class="skill-bar">
              <h6>Illustrator</h6>
              <ol class="skill-progress">
                <li class="skill-complete"><span>0%</span></li>
                <li class="skill-complete"><span>10%</span></li>
                <li class="skill-complete"><span>20%</span></li>
                <li class="skill-complete"><span>30%</span></li>
                <li class="skill-complete"><span>40%</span></li>
                <li class="skill-complete"><span>50%</span></li>
                <li class="skill-complete"><span>60%</span></li>
                <li class="skill-complete"><span>70%</span></li>
                <li class="skill-active"><span>85%</span></li>
                <li><span>90%</span></li>
                <li><span>95%</span></li>
                <li><span>100%</span></li>
              </ol>
            </div>
            <div class="skill-bar">
              <h6>After Effect</h6>
              <ol class="skill-progress">
                <li class="skill-complete"><span>0%</span></li>
                <li class="skill-complete"><span>10%</span></li>
                <li class="skill-complete"><span>20%</span></li>
                <li class="skill-complete"><span>30%</span></li>
                <li class="skill-complete"><span>40%</span></li>
                <li class="skill-complete"><span>50%</span></li>
                <li class="skill-complete"><span>60%</span></li>
                <li class="skill-complete"><span>70%</span></li>
                <li class="skill-complete"><span>80%</span></li>
                <li class="skill-complete"><span>85%</span></li>
                <li class="skill-active"><span>97%</span></li>
                <li><span>100%</span></li>
              </ol>
            </div>
          </div>
          <div class="col-12 col-md-6">
            <div class="skill-bar">
              <h6>Html</h6>
              <ol class="skill-progress">
                <li class="skill-complete"><span>0%</span></li>
                <li class="skill-complete"><span>10%</span></li>
                <li class="skill-complete"><span>20%</span></li>
                <li class="skill-complete"><span>30%</span></li>
                <li class="skill-complete"><span>40%</span></li>
                <li class="skill-complete"><span>50%</span></li>
                <li class="skill-complete"><span>60%</span></li>
                <li class="skill-complete"><span>70%</span></li>
                <li class="skill-complete"><span>80%</span></li>
                <li class="skill-active"><span>90%</span></li>
                <li><span>95%</span></li>
                <li><span>100%</span></li>
              </ol>
            </div>
            <div class="skill-bar">
              <h6>CSS</h6>
              <ol class="skill-progress">
                <li class="skill-complete"><span>0%</span></li>
                <li class="skill-complete"><span>10%</span></li>
                <li class="skill-complete"><span>20%</span></li>
                <li class="skill-complete"><span>30%</span></li>
                <li class="skill-complete"><span>40%</span></li>
                <li class="skill-complete"><span>50%</span></li>
                <li class="skill-complete"><span>60%</span></li>
                <li class="skill-complete"><span>70%</span></li>
                <li class="skill-active"><span>85%</span></li>
                <li><span>90%</span></li>
                <li><span>95%</span></li>
                <li><span>100%</span></li>
              </ol>
            </div>
            <div class="skill-bar">
              <h6>Javascript</h6>
              <ol class="skill-progress">
                <li class="skill-complete"><span>0%</span></li>
                <li class="skill-complete"><span>10%</span></li>
                <li class="skill-complete"><span>20%</span></li>
                <li class="skill-complete"><span>30%</span></li>
                <li class="skill-complete"><span>40%</span></li>
                <li class="skill-complete"><span>50%</span></li>
                <li class="skill-complete"><span>60%</span></li>
                <li class="skill-active"><span>72%</span></li>
                <li><span>78%</span></li>
                <li><span>80%</span></li>
                <li><span>90%</span></li>
                <li><span>100%</span></li>
              </ol>
            </div>
            <!-- End Range Sliders -->
          </div>
        </div>
      </div>
    </div>
    <div class="section"></div>
  </section>
</template>

<script>
export default {
  name: "SkillSection",
};
</script>

<style scoped>
#skill .container {
  min-height: 55vh;
  min-width: 100%;
  display: flex;
  align-items: center;
  background-color: rgba(0, 184, 148, 255);
}
h3 {
  color: rgba(255, 255, 255, 255);
  font-family: "Roboto Slab", serif;
  font-weight: bold;
  font-size: 35px;
  text-align: left;
  padding-top: 5rem;
  margin-bottom: 2rem;
  text-decoration-line: underline;
  text-decoration-style: solid;
  text-decoration-color: rgba(51, 198, 169, 255);
  text-decoration-thickness: 5px;
  text-decoration-skip-ink: none;
}
.skill {
  flex-direction: column;
}
.skill-top {
  max-width: 70vw;
  margin: 0 auto;
}
/* Range Sliders CSS */
h6 {
  color: white;
  font-size: 12px;
  font-family: "Roboto Slab", serif;
  line-height: 1.5;
  font-weight: lighter;
  padding-bottom: 0;
}
.skill-bar {
  margin: 0 1rem 2rem 1rem;
}
.skill-progress {
  display: flex;
  justify-content: space-between;
  list-style: none;
  padding: 0;
  margin: 0 0 1rem 0;
}
.skill-progress li {
  flex: 2;
  position: relative;
  padding: 0 0 14px 0;
  font-size: var(--font-size-default);
  line-height: 1.5;
  color: white;
  font-weight: 600;
  white-space: nowrap;
  overflow: visible;
  min-width: 0;
  text-align: center;
  border-bottom: 3px solid rgba(77, 205, 180, 255);
}
.skill-progress li:first-child,
.skill-progress li:last-child {
  flex: 1;
}
.skill-progress li:last-child {
  text-align: right;
}
.skill-progress li:before {
  content: "";
  display: block;
  width: 8px;
  height: 8px;
  background-color: transparent;
  border-radius: 50%;
  border: 6px solid transparent;
  position: absolute;
  left: calc(50% - 6px);
  bottom: -7px;
  z-index: 3;
  transition: all 0.2s ease-in-out;
}
.skill-progress li:first-child:before {
  left: 0;
}
.skill-progress li:last-child:before {
  right: 0;
  left: auto;
}
.skill-progress span {
  transition: opacity 0.3s ease-in-out;
}
.skill-progress li:not(.skill-active) span {
  opacity: 0;
}
.skill-progress .skill-complete:not(:first-child):after,
.skill-progress .skill-active:not(:first-child):after {
  content: "";
  display: block;
  width: 100%;
  position: absolute;
  bottom: -2px;
  left: -50%;
  z-index: 2;
  border-bottom: 3px solid white;
}
.skill-progress li:last-child span {
  width: 200%;
  display: inline-block;
  position: absolute;
  left: -100%;
}
.skill-progress .skill-complete:last-child:after,
.skill-progress .skill-active:last-child:after {
  width: 200%;
  left: -100%;
}
.skill-progress .skill-complete:before {
  background-color: transparent;
}
.skill-progress .skill-active:before,
.skill-progress li:hover:before,
.skill-progress .skill-hovered:before {
  background-color: white;
  border-color: transparent;
}
.skill-progress li:hover:before,
.skill-progress .skill-hovered:before {
  transform: scale(1.33);
}
.skill-progress li:hover span,
.skill-progress li.skill-hovered span {
  opacity: 1;
}
.skill-progress:hover li:not(:hover) span {
  opacity: 0;
}
.skill-container {
  width: 80%;
}
</style>
