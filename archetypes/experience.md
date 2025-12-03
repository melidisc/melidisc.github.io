---
title: {{ replace .Name "-" " " | title }}
type: experience
date: {{ .Date }}
draft: false
---

# Professional Experience

<!-- Use the experience-item shortcode for consistent formatting -->

{{</* experience-item 
  title="Job Title"
  company="Company Name"
  link="https://company-website.com"
  location="City, Country"
  startDate="Jan 2020"
  endDate="Present"
*/>}}
* Responsibility or achievement 1
* Responsibility or achievement 2
* Responsibility or achievement 3
{{</* /experience-item */>}}

{{</* experience-item 
  title="Previous Role"
  company="Previous Company"
  link="https://previous-company.com"
  location="City, Country"
  startDate="Jan 2018"
  endDate="Dec 2019"
*/>}}
* Responsibility or achievement 1
* Responsibility or achievement 2
* Responsibility or achievement 3
{{</* /experience-item */>}}

# Education

{{</* experience-item 
  title="Degree Name"
  company="University Name"
  link="https://university.edu"
  location="City, Country"
  startDate="Sep 2014"
  endDate="Jun 2018"
*/>}}
* Achievement or focus area
* Thesis or notable project
* Relevant coursework
{{</* /experience-item */>}}