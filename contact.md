---
layout: page
title: Contact
permalink: /contact/
---

<div class="sqs-layout sqs-grid-12 columns-12" data-type="page" data-updated-on="1519261819576" id="page-5a8ba4e1652deaeaab4cc1a4">
  <div class="row sqs-row" id="yui_3_17_2_1_1540853799111_96">
    <div class="col sqs-col-8 span-8" id="yui_3_17_2_1_1540853799111_95">
      <div class="sqs-block image-block sqs-block-image sqs-text-ready" data-aspect-ratio="58.41059602649007" data-block-type="5" id="block-yui_3_17_2_9_1519175149212_31872">
        <div class="sqs-block-content" id="yui_3_17_2_1_1540853799111_94">
          <div class="image-block-outer-wrapper layout-caption-below design-layout-inline   " id="yui_3_17_2_1_1540853799111_93">
            <div class="intrinsic" style="max-width:1498.0px;" id="yui_3_17_2_1_1540853799111_92">
              <div style="padding-bottom: 58.4106%; overflow: hidden;background-image:url(/assets/images/workstation.jpg); background-size:cover;" class="image-block-wrapper has-aspect-ratio">
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="col sqs-col-4 span-4">
      <div class="sqs-block html-block sqs-block-html" data-block-type="2" id="block-yui_3_17_2_4_1519174341173_18185">
        <div class="sqs-block-content">
          <h3>Contact</h3>
          <h4>Johnny Whichard</h4>
          <p>Product Manager and Operations at Octi</p>
          <p>
            {%- if site.phone_number -%}
              <a target="_blank" href="tel:{{ site.phone_number }}">{{ site.phone_number }}</a>
            {%- endif -%}
          </p>
          <p>
            {%- if site.linkedin_username -%}
              <a target="_blank" href="https://www.linkedin.com/in/{{ site.linkedin_username| cgi_escape | escape }}">LINKEDIN</a>
            {%- endif -%}
          </p>
          <p>
            {%- if site.email -%}
              <a target="_blank" href="mailto:{{ site.email }}">EMAIL</a>
            {%- endif -%}
          </p>
        </div>
      </div>
      <div class="sqs-block form-block sqs-block-form" data-block-type="9" id="block-82f5d43615f59e631d6e">
        <div class="sqs-block-content">
          <div class="form-wrapper">
            <div class="form-inner-wrapper">
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
