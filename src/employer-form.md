---
layout: default.liquid
---

<style>
  input {width: 100%}
  .form-control {
    background: white;
    border: 1px solid;
  }
</style><div class="container">

<div class="container">
  <h1 class="quick-size-fix" style="margin-top:20px">TELL US WHO YOU NEED</h1>
  <h2 style="text-align: center">USE OUR SIMPLE SUBMISSION FORM TO GET STARTED</h2>
  <div style="display:none; text-align:center;" id="thankyou_message">
  <h2>Thanks for contacting us!
  We will get back to you soon!</h2>
  </div>
  <div role="form" class="wpcf7" id="wpcf7-f5985-p5986-o1" lang="en-US" dir="ltr">
    <form id="gform" action="https://script.google.com/macros/s/AKfycbw_pyPtUQU1oITCRARHy8j1c9OOlXBJnmQ3r6q1/exec" method="post" class="wpcf7-form" novalidate="novalidate">
      <fieldset class="pure-group">
        <div style="display: none;">
          <!--input id must be honeypot or else it wont work-->
          <label class="sr-only">Keep this field blank</label>
          <input title="honeypot" id="honeypot" type="text" name="honeypot" value="" />
          <!--the rest of your form-->
        </div>
        <label for="Company Name">Company Name*</label>
        <br />
        <span class="wpcf7-form-control-wrap CompanyName">
          <input id="Company Name" name="Company Name" type="text" value="" size="40" class="wpcf7-form-control wpcf7-text wpcf7-validates-as-required" aria-required="true" aria-invalid="false" tabindex="0" />
        </span>
        <label for="Contact Person">Contact Person*</label>
        <br />
        <span class="wpcf7-form-control-wrap your-name">
          <input id="Contact Person"type="text" name="Contact Person" value="" size="40" class="wpcf7-form-control wpcf7-text wpcf7-validates-as-required   " aria-required="true" aria-invalid="false" tabindex="0" />
        </span>
        <label for="email">Email Address*</label>
        <br />
        <span class="wpcf7-form-control-wrap your-email">
          <input id="email" type="email" name="email" value="" size="40" class="wpcf7-form-control wpcf7-text wpcf7-email wpcf7-validates-as-required wpcf7-validates-as-email" aria-required="true" aria-invalid="false" tabindex="0" />
        </span>
        <label for="Cell Phone">Cell Phone Number*</label>
        <br />
        <span class="wpcf7-form-control-wrap tel-186">
          <input id = "Cell Phone" type="tel" name="Cell Phone" value="" size="40" class="wpcf7-form-control wpcf7-text wpcf7-tel wpcf7-validates-as-required wpcf7-validates-as-tel" aria-required="true" aria-invalid="false" tabindex="0" />
        </span>
        <label for="Company Website">Company Website</label>
        <br />
        <span class="wpcf7-form-control-wrap website">
          <input id="Company Website" type="text" name="Company Website" value="" size="40" class="wpcf7-form-control wpcf7-text" aria-invalid="false" tabindex="0" />
        </span>
        <label for="About Your Company">Anything else you want to tell us about your company?</label>
        <br />
        <span class="wpcf7-form-control-wrap AboutYourCompany">
          <textarea id="About Your Company" name="About Your Company" cols="40" rows="10" class="wpcf7-form-control wpcf7-textarea form-control" aria-invalid="false" tabindex="0"></textarea>
        </span>
        <br />
        <label for="Position Title">Title of Position</label>
        <br />
        <span class="wpcf7-form-control-wrap Position">
          <input id="Position Title" type="text" name="Position Title" value="" size="40" class="wpcf7-form-control wpcf7-text" aria-invalid="false" tabindex="0" />
        </span>
        <label for="Position Type">Type of Position</label>
        <br />
        <span class="wpcf7-form-control-wrap PositionType">
          <select id="Position Type" name="Position Type" class="wpcf7-form-control wpcf7-select" aria-invalid="false" tabindex="0">
            <option value="Full Time" tabindex="0">Full Time</option>
            <option value="Part Time" tabindex="0">Part Time</option>
            <option value="Freelance" tabindex="0">Freelance</option>
          </select>
        </span>
        <br />
        <label for="City and State">City and State where will position be located, unless work-from-home position</label>
        <br />
        <span class="wpcf7-form-control-wrap CityState">
          <input id = "City and State" type="text" name="City State" value="" size="40" class="wpcf7-form-control wpcf7-text" aria-invalid="false" tabindex="0" />
        </span>
        <label for="Job Description">Position Job Description</label>
        <br />
        <span class="wpcf7-form-control-wrap JobDescription">
          <textarea id="Job Description" name="Job Description" cols="40" rows="10" class="wpcf7-form-control wpcf7-textarea form-control" aria-invalid="false" tabindex="0"></textarea>
        </span>
        <label>Position Type</label>
        <br />
        <span class="wpcf7-form-control-wrap radio-561">
          <span class="wpcf7-form-control wpcf7-radio">
            <span class="wpcf7-list-item first">
              <input title="Salary Button"type="radio" name="Pay Type" value="Salary" tabindex="0" style="width:10px" />
              <span class="wpcf7-list-item-label">Salary</span>
            </span>
            <span class="wpcf7-list-item last">
              <input title = "Hourly button"type="radio" name="Pay Type" value="Hourly" tabindex="0" style="width:10px"/>
              <span class="wpcf7-list-item-label">Hourly</span>
            </span>
          </span>
        </span>
        <br />
        <label for ="Pay Amount">Position Pay Amount</label>
        <br />
        <span class="wpcf7-form-control-wrap PayAmount">
          <input id="Pay Amount" type="text" name="Pay Amount" value="" size="40" class="wpcf7-form-control wpcf7-text" aria-invalid="false"  tabindex="0"/>
        </span>
        <label for ="Candidate Skills">Top 3 Candidate Skills</label>
        <br />
        <span class="wpcf7-form-control-wrap Skill1">
          <input title="Skill1" type="text" name="Skill1" value="" size="40" class="wpcf7-form-control wpcf7-text" aria-invalid="false"  tabindex="0"/>
        </span>
        <span class="wpcf7-form-control-wrap Skill2">
          <input title="Skill2" type="text" name="Skill2" value="" size="40" class="wpcf7-form-control wpcf7-text" aria-invalid="false" tabindex="0" />
        </span>
        <span class="wpcf7-form-control-wrap Skill3">
          <input title="Skill3" type="text" name="Skill3" value="" size="40" class="wpcf7-form-control wpcf7-text" aria-invalid="false" tabindex="0" />
        </span>
        <label for="Candidate Traits">Top 3 Candidate Personality Traits
        <br />
        <span class="wpcf7-form-control-wrap Trait1">
          <input title="Trait1"type="text" name="Trait1" value="" size="40" class="wpcf7-form-control wpcf7-text" aria-invalid="false"  tabindex="0"/>
        </span>
        <span class="wpcf7-form-control-wrap Trait2">
          <input title="Trait2"type="text" name="Trait2" value="" size="40" class="wpcf7-form-control wpcf7-text" aria-invalid="false"  tabindex="0"/>
        </span>
        <span class="wpcf7-form-control-wrap Trait3">
          <input title="Trait3"type="text" name="Trait3" value="" size="40" class="wpcf7-form-control wpcf7-text" aria-invalid="false"  tabindex="0"/>
        </span>
        <label for="Anything Else">Anything Else You Want to Tell Us?</label>
        <br />
        <span class="wpcf7-form-control-wrap AnythingElse">
          <textarea id="Anything Else" name="Anything Else" cols="40" rows="10" class="wpcf7-form-control wpcf7-textarea form-control" aria-invalid="false" tabindex="0"></textarea>
        </span>
        <input type="submit" value="Send" class="wpcf7-form-control wpcf7-submit btn tsg-btn quick-btn-fix"  tabindex="0" style="width: 10%"/>
      </fieldset>
      <div class="wpcf7-response-output wpcf7-display-none"></div>
    </form>
  </div>
</div>

<script data-cfasync="false" type="text/javascript" src="/js/form-submission-handler.js"></script>
