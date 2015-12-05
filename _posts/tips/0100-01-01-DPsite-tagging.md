---
tipid: IDPsite-tagging
title: IDP Site Tagging Scheme
category: tip
layout: tip-preview
images:
  - image:
     size: large
tags: [Nepal, Kathmandu, Earthquake, IDP, Camp]
---

<a href="{{ site.baseurl }}/guide/Nepal-IDP-site-updating-guide.html#IDP-update-intro"> IDP settlements </a>and <a href="{{ site.baseurl }}/guide/Nepal-IDP-site-updating-guide.html#IDPtent-update"> IDP tents </a> both share the same tagging scheme

###idp:camp_site=spontaneous_camp
###damage:event=nepal_earthquake_2015

###idp:status_yyyymmdd={new,increased,decreased, or empty}

####ex:
####idp:status_20150427=new
####idp:status_20150503=decreased

###idp:source_yyyymmdd={add appropriate source}

####ex:
####idp:source_20150427=CNES, Airbus DS
####idp:source_20150503=GeoEye1 DigitalGlobe

####You can see in the examples above you have two idp:source tags because you used two imagery source to evaluate the change in the IDP site. You also have two idp:status tags to record the status at two times.
