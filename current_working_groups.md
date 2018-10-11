---
layout: page
heading: Current Working Groups
subheading: 
full_footer: false
header_content: false
---


<div class="row bigtext" markdown="1">
<div class="col-sm-8 col-sm-offset-2" markdown="1">


## Current Working Groups
The following are active and proposed working groups. Working group documentation, meeting notes, and outputs are maintained by each working group. 

{% assign sorted = site.data.working_groups['working_groups'] | sort: 'name' %}
{% for group in sorted %}
  <h3 style="margin-top: 20px">{{group.name}}</h3>

 <div class="row">
  <div class="col-sm-2"><b>Coordinator(s):</b></div>
  <div class="col-sm-10">{{group.coordinator | markdownify}}
  </div>
 </div>
 <div class="row">
  <div class="col-sm-2"><b>Status:</b></div>
  <div class="col-sm-10">{{group.status}}</div>
 </div>
 <div class="row">
  <div class="col-sm-2"><b>Description:</b></div>
  <div class="col-sm-10"> {{group.description}}</div>
 </div>
 <div class="row">
  <div class="col-sm-2"><b>Website:</b></div>
  <div class="col-sm-10"><a href="{{group.url}}">URL</a></div>
 </div> 

{% endfor %}
