---
layout: page
heading: WT / RDA-US Early Career Fellows
subheading: 
full_footer: false
header_content: false
---


<div class="row bigtext" markdown="1">
<div class="col-sm-8 col-sm-offset-2" markdown="1">



## Joint Whole Tale / RDA-US Early Career Fellows

The Whole Tale project, in cooperation with the US region of the Research Data Alliance (RDA/US) and its [early career fellowship program RDA/US Data Share](http://us.rd-alliance.org/early-programs-fellowship), developed this fellowship program to encourage engagement of early-career professionals with both the WT and RDA communities to explore issues related to reproducibility, provenance, sharing, and citation in computational research across a variety of domains. All fellows will participate in the 2019 RDA 13th plenary.  Four fellows will engage in  6-month projects pursuing issues relevant to the WT and RDA communities.

{% assign fellows = site.data.rda_fellows['rda_fellows']  %}
{% for fellow in fellows %}
 <div class="row" style="margin-bottom:20px"> 
  <div class="col-sm-2" style="margin-top:20px"><img src="assets/images/rda_fellows/{{fellow.image}}"></div>
  <div class="col-sm-10">
      <div><h3><b>{{fellow.name}}</b>, <i>{{fellow.title}}</i></h3></div>
      {% if fellow.project %}
          <div style="margin-top:10px"><b>Project title:</b> <i>{{fellow.project}}</i></div>
      {% endif %}
      <div style="margin-top:10px"><b>Working/Interest groups:</b> {{fellow.wg_ig}}</div>
      <div style="margin-top:10px">{{fellow.bio}}</div>
  </div>
 </div>
{% endfor %}
