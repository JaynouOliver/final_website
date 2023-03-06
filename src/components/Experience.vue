<template>
  <div>
    <h2>Experience</h2>
    <div class="timeline">
      <div class="year-container">
        <span class="year">2022</span>
      </div>
      <ul>
        <br><br><br>
        <li>
          <div class="content">
            <a href="https://projectx.cloud/" target="_blank">
              <h3>ProjectX Cloud Technologies</h3>
              <h5>Co-founder and Director</h5>
              <div class="grey">June 2022 - Present</div>
              <br>
              <div>
                - A <strong>Startup India recognized</strong> Cloud Computing startup focusing on creating a whole new Operating System where applications run on the cloud.
                Pitched to <strong>7+ VCs</strong> and got incubated under <strong>NVIDIA Inception Program</strong>
                <br><br>
                - Currently working with the Financial Team.
              </div>

            </a>
          </div>
        </li>
        <li>
          <div class="content">
            <a href="https://cloudsek.com" target="_blank">
              <h3>Virginia Tech</h3>
              <h5>Student Hackathon Mentor</h5>
              <div class="grey">Feb 2022</div>
              <br>
              <p>
                - I was offered the Mentor Position at Virginia Tech, one of the leading engineering institutes in the USA. guided students on the field of Machine Learning.
                <br><br>
              </p>
            </a>
          </div>
        </li>
        <li>
          <div class="content">
            <a href="https://cloudsek.com" target="_blank">
              <h3>Ahmedabad University</h3>
              <h5>Student Hackathon Mentor</h5>
              <div class="grey">Jan 2022</div>
              <br>
              <p>
                - Was appointed as the Mentor to guide students in the field of Open Source and Machine Learning in the Hackathon - <strong>Ingenium</strong>.
                <br><br>
              </p>
            </a>
          </div>
        </li>
        <li>
          <div class="content">
            <a href="https://cloudsek.com" target="_blank">
              <h3>Neurologic</h3>
              <h5>Machine Learning Engineer</h5>
              <div class="grey">Dec 2022</div>
              <br>
              <p>
                - Worked on <strong> Application Tracking System</strong>, Implemented ML Model using BERT with 90% accuracy
                <br><br>
              </p>
            </a>
          </div>
        </li>
        <br> <br>
      </ul>
      <div class="year-container">
        <span class="year">2021</span>
      </div>
      <ul>
        <br> <br> <br>
        <li>
          <div class="content align-left">
            <a href="https://seclogic.io" target="_blank">
              <h3>Yale University</h3>
              <h5>Top 40s in Position in Hackathon</h5>
              <div class="grey">Dec 2021 - Jan 2022</div>
              <br>
              <p>
                - Worked on an <strong>Ambulance WhatsApp chatbot</strong> that gives you live locatoin, address and contacts of nearby ambulances and hospitals near you accourding to your location.
              </p>
            </a>
          </div>
        </li>
      </ul>
      <div class="green-dot"></div>
    </div>
  </div>
</template>

<script>

export default {
  name: "Experience",
}
</script>
<style scoped>
h2 {
  font-weight: 500;
  color: white;
  font-size: 1.8rem;
  border-bottom: 10px solid green;
  line-height: 0.4;
  width: 60px;
  transition: all ease 0.3s;
  margin-bottom: 2rem;
}

strong {
  font-weight: 500;
  color: #1DB954;
}

a {
  color: white;
  border: none;
  text-decoration: none;
}

.green-dot {
  width: 16px;
  height: 16px;
  background: #1DB954;
  border-radius: 50%;
  margin-left: -0.45em;
}

.year-container {
  position: absolute;
  margin: 0 -2.25em;
  z-index: 9999;
}

.year {
  color: white;
  font-weight: 500;
  font-size: 1.5rem;
  background: #1DB954;
  border-radius: 16px;
  padding: 0.5rem;
}

h2:hover {
  font-size: 1.8rem;
  font-weight: 500;
  color: white;
  border-bottom: 10px solid #1DB954;
  line-height: 0.4;
  width: 100px;
  transition: all ease 0.3s;
}

div {
  color: white;
  font-family: "canada-type-gibson" !important;
}

* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  font-family: 'canada-type-gibson', sans-serif;
  perspective: 800px;
}

.grey {
  color: #ddd;
  font-size: 0.9rem;
}

body {
  display: flex;
}

.timeline {
  width: 100%;
  background-color: #1a202c;
  color: #fff;
  padding: 30px 20px;
  word-wrap: normal;
}

.timeline ul {
  list-style-type: none;
  border-left: 2px solid white;
  padding: 10px 5px;
}

.timeline ul li {
  padding: 20px 20px;
  position: relative;
  cursor: pointer;
  transition: .5s;
}

.timeline ul li span {
  display: inline-block;
  border-radius: 25px;
  padding: 2px 5px;
  font-size: 15px;
  text-align: center;
}

.timeline ul li .content h3 {
  color: #1DB954;
  font-size: 1.6rem;
  padding-top: 5px;
  font-weight: 500;
  margin-bottom: 0.2rem;
}

h5 {
  font-size: 1.2rem;
  padding-top: 5px;
  font-weight: 500;
  margin-bottom: 8px;
}

.timeline ul li .content p {
  padding: 5px 0px 15px 0px;
  font-size: 15px;
}

.timeline ul li:before {
  position: absolute;
  content: '';
  width: 10px;
  height: 10px;
  background-color: lawngreen;
  border-radius: 50%;
  left: -11px;
  top: 28px;
  transition: .5s;
  margin: 0;
}

.timeline ul li:hover {
  background-color: #1b405e;
  border-radius: 8px;
}

.timeline ul li:hover:before {
  background-color: #0F0;
  box-shadow: 0px 0px 10px 2px #0F0;
}

@media (max-width: 300px) {
  .timeline {
    width: 100%;
    padding: 30px 5px 30px 10px;
  }

  .timeline ul li .content h3 {
    color: #1DB954;
    font-size: 15px;
  }

}
</style>