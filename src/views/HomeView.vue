<template>
  <NavBar />
  <div id="GHRa">
    <div id="fHZd">
      <div id="ii75w" class="gjs-cell">
        <div id="yGnY">Peppu Technologies - Simplifying Technology for Everyone<br></div>
        <div id="81VC" class='bottom'>Discover powerful tools and insightful guides to help you work smarter,
          not harder. We have tools that make everyday living easier through automation.</div>
      </div>
    </div>
    <section class="hero">
      <div class="container">
        <h1>Our Tools</h1>

        <div class="arrow-container">
          <div class="pulse"></div>
          <div class="arrow"></div>
        </div>
        <h3>Google Workspace Add-ons</h3>
        <p>At Peppu technologies, our add-ons have passed the security audit verified by Google and certified
          <span class="highlight">100% compliant</span> with the Google API User Data Policy.
          We build add-ons that make using Google Workspace easier and delightful.
        </p>
      </div>
    </section>

    <section class="accordion">
      <div class="container">
        <div class="accordion-item">
          <a href='https://proctored.peppubuild.com'>
            <div class="accordion-header">
              <div class="accordion-icon">✓</div>
              <div class="accordion-title">Proctored by Peppubuild</div>
              <div class="accordion-toggle">›</div>
            </div>
          </a>
          <div class="accordion-content">
            <div class="accordion-details">
              <p>Turn Google Sheets and Classrooms into an exammination center. Track student activities
                via our AI proctoring software.</p>
              <div class="app-icons">
                <img src="https://upload.wikimedia.org/wikipedia/commons/5/59/Google_Classroom_Logo.png"
                  alt="Google Classrooms" class="app-icon">
                <img src="https://www.google.com/images/about/forms-icon.svg" alt="Google Forms" class="app-icon">
              </div>
            </div>
          </div>
        </div>

        <div class="accordion-item">
          <div class="accordion-header" @click="comingSoon()">
            <div class="accordion-icon">✓</div>
            <div class="accordion-title">PayTrack</div>
            <div class="accordion-toggle">›</div>
          </div>
          <div class="accordion-content">
            <div class="accordion-details">
              <p>Spin out a fully functional e-commerce website from your Google Sheet, track inventories,
                manage accounting, and send invoices, all from your Sheet.</p>
              <div class="app-icons">
                <img src="https://upload.wikimedia.org/wikipedia/commons/3/30/Google_Sheets_logo_%282014-2020%29.svg"
                  alt="Google Sheets" class="app-icon">
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="hero">
      <div class="container">
        <h3>Peppubuild</h3>
        <p>Create your SEO compliant web applications without writing any code, add HTML, CSS, and JavaScript
          code when necessary, own your code without vendor lock-in. </p>
      </div>
    </section>
    <section class="accordion">
      <div class="container">
        <div class="accordion-item">
          <a href='/products/peppubuild'>
            <div class="accordion-header">
              <div class="accordion-icon">✓</div>
              <div class="accordion-title">Peppubuild</div>
              <div class="accordion-toggle">›</div>
            </div>
          </a>
          <div class="accordion-content">
            <div class="accordion-details">
              <p>Build stunning websites and publish faster with Peppubuild.</p>
              <div class="app-icons">
                <img src="../assets/logo.jpeg" alt="Peppubuild" class="app-icon">
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="hero">
      <div class="container">
        <h3>Custom Software</h3>
        <p>Our custom software ranges from educational tools, to marine predictive maintenance systems and logistics tracking, to make daily tasks easier and faster. </p>
      </div>
    </section>
    <section class="accordion">
      <div class="container">
        <div class="accordion-item">
          <div class="accordion-header" @click="comingSoon()">
            <div class="accordion-icon">✓</div>
            <div class="accordion-title">Marine Logistics & Maintenance</div>
            <div class="accordion-toggle">›</div>
          </div>
          <div class="accordion-content">
            <div class="accordion-details">
              <p>Tryout our comprehensive tools for maritime companies to manage fleet operations, track
                maintenance schedules, control inventory, ensure regulatory compliance, and optimize
                crew management across vessels.</p>
            </div>
          </div>
        </div>

        <div class="accordion-item">
          <div class="accordion-header" @click="comingSoon()">
            <div class="accordion-icon">✓</div>
            <div class="accordion-title">Marine Survey</div>
            <div class="accordion-toggle">›</div>
          </div>
          <div class="accordion-content">
            <div class="accordion-details">
              <p>Our software streamlines the pre-purchase vessel inspection process by documenting
                structural integrity, equipment condition, and compliance status while generating
                comprehensive digital reports with visual evidence.</p>
            </div>
          </div>
        </div>
      </div>
    </section>
    <div id="ia0lvrl" class="gjs-row">
      <div id="i94jbxr" class="gjs-cell">
        <FooterView />
      </div>
    </div>
  </div>
</template>

<script>
import NavBar from '../components/NavBar.vue'
import FooterView from '../components/FooterView.vue'
export default {
  name: 'HomeView',
  components: { NavBar, FooterView },

  methods: {
    comingSoon() {
      Swal.fire('Coming Soon', 'This product is under review, if you are in our mailing list, we will let you know once it is ready via mail.', 'info')
    }
  }
}
</script>