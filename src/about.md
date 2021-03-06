---
tags: nav
title: About
layout: default.liquid
---
<style>
  .grid {
    display: grid;
    grid-template-columns: repeat(12, [col-start] 1fr);
  }

  .about-hero-img,
  .about-lead-text,
  .about-our-story,
  .about-founders-pic,
  .about__staff,
  .about__staff__team,
  .meet-the-team {
    grid-column: 1 / -1;
  }

  @media all and (min-width: 82.5rem) {
    .about-our-story {
      grid-column: 1 / 7;
    }

    .about-founders-pic {
      grid-column: 7 / 13;
    }
  }
</style>

<div class="grid">

  <div class="about-hero-img" data-aos="fade-up">
      <div class="about-hero-filter"></div>
      <div class="about-hero-text">
        <h1 class="text-light-green text-left" style="font-size: 60px; line-height: .75;">ABOUT US</h1>
        <p style="color:white">We care about the cannabis industry</p>
      </div>
    </div>

  <div class="about-lead-text" data-aos="fade-up">
      <h1 class="text-light-green quick-size-fix">THE FOUNDERS OF THC STAFFING GROUP HAVE OVER 30 COMBINED YEARS OF
        EXPERIENCE AS ACTIVISTS, CONSULTANTS, AND RECRUITERS FOR THE LEGAL CANNABIS MOVEMENT AND INDUSTRY</h1>
      <a href="/about/#meet-the-team"><button type="button" class="btn btn-primary tsg-btn hvr-sweep-to-right">MEET THE
          TEAM</button></a>
    </div>

  <div class="about__staff" data-aos="fade-up">
      <div class="about__staff__founders">
        <p class="fancy">who we are</p>
        <h1>Chief Executive Officer</h1>
        <div class="founder">
          <img alt=" " src="img/about/danielle-new.jpg">
          <div class="bio">
          <h1>Danielle Schumacher</h1>
          <p>She/Her/Hers</p>
          <p>Danielle Schumacher is a seasoned activist with experience running cannabis businesses across the
              country.
              As
              the first chancellor of Oaksterdam University, Danielle worked with Richard Lee to establish America’s
              first
              cannabis college. She has been quoted by various media outlets including The Associated Press, Fox News,
              CNBC,
              and San Francisco Chronicle.</p>
            <p>Danielle was recruited by Berkeley Patients Group in 2005 to head the Cannabis Action Network. Danielle
              has
              served as office manager for internationally-respected authority on cannabis Chris Conrad and activist
              author
              Mikki Norris, and for noted practitioners Frank Lucido MD and Maria Mangini PhD FNP. Danielle was
              Executive
              Director of Illinois NORML and held the Youth Seat on the National NORML Board of Directors. She was named
              Freedom Fighter by High Times Magazine at age 22. Danielle co-founded the University of Illinois chapter
              of
              Students for Sensible Drug Policy in 2001. She earned a degree in anthropology in 2004, graduating with
              highest distinction.</p>
            <p>Danielle serves as the current President & CEO of THC Staffing Group and continues her mission of
              perpetuating diversity and inclusion in the legal cannabis industry.</p>
          </div>
        </div>
      </div>
    </div>
    <div class="about__staff__team" id="meet-the-team" data-aos="fade-up">
      <h1 style="text-align: left;">The team</h1>
      <div class="headshots">
        <div class="headshot active">
          <img id="jesseHeadshot" alt=" " src="img/about/jesse-headshot.jpg" data-staffer="jesse" />
        </div>
        <div class="headshot">
          <img id="richardHeadshot" alt=" " src="img/about/richard-headshot.jpg" data-staffer="richard">
        </div>
        <div class="headshot">
          <img id="tiffanyHeadshot" alt=" " src="img/about/tiffany-headshot.jpg" data-staffer="tiffany">
        </div>
      </div>
      <div class="staff__bio">
        <div class="staff__bio__left">
          <h1 id="staffName" style="color: black; text-align: left;">Jesse Stout</h1>
          <p id="staffPronouns">He/Him/His</p>
        </div>
        <div class="staff__bio__right">
          <p id="staffBio">
            Jesse is passionate about reducing the harms of incarceration. Previously, Jesse advocated for criminal
            justice reform as Policy Director of the nonprofit Legal Services for Prisoners with Children. A graduate of
            Brown University and UC Hastings College of the Law, he helped start the Students for Sensible Drug Policy
            chapters at both schools. He has received awards including the Daily Journal CLAY Award (2016), SF Human
            Rights Commission HERO Award for Organizations Advancing Civil Rights (2014), SF Board of Supervisors
            Certificate of Honor (2014), the NORML Student Activist Award (2010), and the High Times Freedom Fighter of
            the Month Award (2007). Jesse practices business law with Greenbridge Corporate Counsel, and is based in San
            Francisco.
          </p>
        </div>
      </div>
    </div>
  </div>
  <script src="js/staffBios.js"></script>