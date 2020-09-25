---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

## Level of emergency


<ul>
{% for entity in site.data.tcev %}
<li>Title: {{ entity.title }}</li>
{% endfor %}
</ul>
<i class="fas fa-university"></i> Antipolo City Hall <br />
<i class="fas fa-bacteria"></i> Covid-19 <br />

### <i class="fas fa-home"></i> Village
* <i class="fas fa-shield-alt"></i> Village Security
* <i class="fas fa-toolbox"></i> Home Repair
* <i class="fas fa-wrench"></i> Auto Mechanic

### <i class="fas fa-users"></i> Barangay
* <i class="fas fa-bullhorn"></i> Police Department
* <i class="fas fa-hospital-alt"></i> Ambulance/Hospital
* <i class="fas fa-fire-extinguisher"></i> Fire Department

### <i class="fas fa-city"></i> City
* <i class="fas fa-hand-holding-medical"></i> Red Cross
* Covid-19

### <i class="fas fa-hard-hat"></i> Utilities
* Manila Water
* Meralco
* PLDT
* Globe Telecom
* Smart Communications

### Other
* NDRRMC
* Civil Defense
* DSWD
* WCPC
* VAWCD
* PCW