---
title: About
permalink: /about/
layout: page
section: about
---
<h3 class="bg-primary text-white radius-lg padding-1 font-sans-xs">Office of the Chief Statistician</h3>
<p>The U.S. Chief Statistician promotes integration across the federal statistical system by chairing the Interagency Council on Statistical Policy (ICSP). The chief statistician also represents the U.S. as a member of the United Nations Statistical Commission and serves as chief of the Statistical and Science Policy Branch, supervising a staff of senior scientists and statisticians who assist with implementation of the federal statistical program and oversee government-wide implementation of the Information Quality Act.</p>

<h3 class="bg-primary text-white radius-lg padding-1 font-sans-xs">Interagency Council on Statistical Policy</h3>
<p>Started in 1989, the Interagency on Statistical Policy (ICSP) was created to improve communication among the federal statistical agencies. The Evidence-Based Policymaking Act (2018) expanded membership to include departmental statistical units and established the Statistical Official role, which each member of ICSP is designated. The ICSP, led by the U.S. Chief Statistician, sets strategic goals for modernizing the production of federal statistics. The ICSP also plays a leading role in implementing the Evidence-Based Policymaking Act and the Federal Data Strategy.</p>

<h3 class="bg-primary text-white radius-lg padding-1 font-sans-xs">Federal Statistical System</h3>
<p>The Federal Statistical System has a long history of collecting data to produce high quality official statistics. Comprised of 13 principal statistical agencies and 90 plus additional agencies and units engaged in statistical activities, the Federal Statistical System obtains statistical policy guidance and coordination functions from the Office of Management and Budget (OMB), in which leadership of the Interagency for Statistical Policy (ICSP) is located. OMB's responsibilities include but are not limited to:</p>
<ul class="usa-list">
  <li>Ensuring that agencies' budget proposals are consistent with Statistical System priorities</li> 
  <li>Developing and implementing government-wide policies, principles, standards, and guidelines</li>
  <li>Evaluating statistical program performance and agency compliance with policies, principles, standards, and guidelines</li>
  <li>Approving all agency information collections</li>
  <li>Promoting the sharing of statistical information consistent with privacy rights and confidentiality pledges</li>
  <li>Coordinating participation in international statistical activities, including the development of comparable statistics</li>
  <li>Leading and working with interagency councils to facilitate statistical functions and activities</li>
  <li>Providing opportunities for training in statistical policy functions to employees of the Federal Government</li>
</ul>
<hr>
<h3 class="bg-primary text-white radius-lg padding-1 font-sans-xs">Principal Statistical Agencies</h3>
<div class="grid-row grid-gap">
{% for agency in site.agencies %}
  <div class="tablet:grid-col-6 padding-y-2">
    <div class="grid-row border-base-lighter border-solid border-width-1px border-top-width-05 radius-lg shadow-4 font-sans-3xs" style="min-height: 130px">
      <div class="grid-col-4 display-flex flex-row flex-align-center padding-x-2">
        <img src="{{ site.baseurl }}/assets/img/agency_logos/{{ agency.short }}.png" alt="{{ agency.title }} logo">
      </div> 
      <div class="grid-col-8 padding-right-2">
        <p><a href="{{ agency.url }}" target="_blank" class="usa-link--external text-no-underline text-primary">{{ agency.title }}</a></p>
      </div>
    </div>
  </div>
{% endfor %}
</div>