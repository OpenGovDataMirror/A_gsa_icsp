---
title: Interagency Council on Statistical Policy
layout: page
section: about
---
<p>Started in 1989, the Interagency on Statistical Policy (ICSP) was created to improve communication among the federal statistical agencies. The Evidence-Based Policymaking Act (2018) expanded membership to include departmental statistical units and established the Statistical Official role, which each member of ICSP is designated. The ICSP, led by the U.S. Chief Statistician, sets strategic goals for modernizing the production of federal statistics. The ICSP also plays a leading role in implementing the Evidence-Based Policymaking Act and the Federal Data Strategy.</p>

<div class="grid-row grid-gap">
{% for member in site.members %}
  <div class="tablet:grid-col-6 padding-y-2">
    <div class="grid-row border-base-lighter border-solid border-width-1px border-top-width-05 radius-lg shadow-4 font-sans-3xs" style="min-height: 130px">
      <div class="grid-col-4 display-flex flex-row flex-align-center padding-x-2">
        <img src="{{ site.baseurl }}/assets/img/agency_logos/{{ member.agency_short }}.png" alt="{{ member.agency_long }} logo">
      </div> 
      <div class="grid-col-8 padding-right-2">
        <h2>{{ member.name }}</h2>
        <p>{{ member.agency_long }}</p>
        <!--<a href="mailto:{{ member.email }}">{{ member.email }}</a>-->
      </div>
    </div>
  </div>
{% endfor %}
</div>