<template>
  <div class="footer-container d-flex align-items-center justify-content-center">
      <div class="row row-cols-4">
          <div class="contact-container py-5 col">
                <div class="footer-description">
                  <p>A Functional HTML Template for Corporate & Business</p>
                </div>
                <div class="number-container">
                    <i class="fas fa-phone-alt d-inline-block me-2"></i>
                    <p class="d-inline-block">
                        +1 (305) 1234-5678
                    </p>
                </div>
                <div class="email-container">
                    <i class="far fa-envelope d-inline-block me-2"></i>
                    <p class="d-inline-block">hello@example.com</p>
                </div>
                <div class="location-container">
                    <i class="fas fa-map-marker-alt d-inline-block me-2"></i>
                    <p class="d-inline-block">Main Avenue, 987</p>
                </div>
                <div class="button-container">
                    <button type="button" class="btn btn-dark button-border">GET IN TOUCH</button>
                </div>
          </div>
            <div class="about-container col py-5 gx-4">
                <div class="about-title">
                    <h4>About</h4>
                </div>
                <div class="about-list">
                    <ul>
                        <li v-for="about in aboutList" :key="about.items">
                            <a href="#">{{ about.items }}</a>
                        </li>
                    </ul>
                </div>
            </div>
            <div class="services-container col py-5 gx-4">
                <div class="services-title">
                    <h4>Services</h4>
                </div>
                <div class="services-list">
                    <ul>
                        <li v-for="services in servicesList" :key="services.items">
                            <a href="#">{{ services.items }}</a>
                        </li>
                    </ul>
                </div>
            </div>
            <div class="support-container col py-5 gx-4">
                <div class="support-title">
                    <h4>Support</h4>
                </div>
                <div class="support-list">
                    <ul>
                        <li v-for="support in supportList" :key="support.items">
                            <a href="#">{{ support.items }}</a>
                        </li>
                    </ul>
                </div>
            </div>
      </div>
  </div>
</template>

<script>
export default {
    name: "Footer",
    data() {
        return {
            aboutList: [
                {items: "The Company"}, 
                {items: "Institutional"}, 
                {items: "Social & Events"}, 
                {items: "Innovation"},
                {items: "Environment"}, 
                {items: "Technology"} 
            ],
            servicesList: [
                {items: "Audit & Assurance"}, 
                {items: "Financial Advisory"}, 
                {items: "Analytics M&A"}, 
                {items: "Middle Marketing"},
                {items: "Legal Consulting"}, 
                {items: "Regulatory Risk"} 
            ],
            supportList: [
                {items: "Responsibility"}, 
                {items: "Terms of USe"}, 
                {items: "About Cookies"}, 
                {items: "Privacy Policy"},
                {items: "Accessibility"}, 
                {items: "Information"}
            ]
        }
    }
}
</script>

<style>
    .footer-container {
        min-width: 400px;
        background-color: #1c2224;
        color: white;
    }

    .contact-container {
        font-size: 13px;
    }

    .button-border {
        border-color: #96fefe;
    }

    .about-container {
        background-color: #5c5e5e;
    }

    .about-container li {
        list-style-type: "\f054";
    }

    .about-container li a {
        text-decoration: none;
        color: white;
    }

    .services-container {
        background-color: #5c5e5e;
    }

    .services-container li {
        list-style-type: "\f054";
    }

    .services-container li a {
        text-decoration: none;
        color: white;
    }

    .support-container {
        background-color: #5c5e5e;
    }

    .support-container li {
        list-style-type: "\f054";
    }

    .support-container li a {
        text-decoration: none;
        color: white;
    }
</style>