---
# Leave the homepage title empty to use the site title
title: Shizhu Liu
date: 2022-10-24
type: landing

sections:
  - block: v1/about
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: experience
    id: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Clinical Assistant Professor of Mathematics
          company: New York University
          company_url: ''
          company_logo: nyu-logo
          location: New York
          date_start: '2018-09-01'
          date_end: ''
        - title: Director of the Summer Bootcamp, M.S. in the Mathematics in Finance
          company: New York University
          company_url: ''
          company_logo: nyu-logo
          location: New York
          date_start: '2019-08-01'
          date_end: ''
        - title: Adjunct Professor
          company: New York University
          company_url: ''
          company_logo: nyu-logo
          location: New York
          date_start: '2014-09-01'
          date_end: '2018-08-01'
        - title: Acting Director of Undergraduate Studies
          company: Department of Mathematics Tandon School of Engineering NYU
          company_url: ''
          company_logo: nyu-logo
          location: New York
          date_start: '2016-08-01'
          date_end: '2017-08-01'
        - title: Data Science Consultant
          company: Maiden Reinsurance North America
          company_url: ''
          company_logo: maiden-insurance
          location: New York
          date_start: '2017-07-01'
          date_end: '2017-08-31'
        - title: Math Workshop Coordinator
          company: Department of Mathematics Tandon School of Engineering NYU
          company_url: ''
          company_logo: nyu-logo
          location: New York
          date_start: '2013-09-01'
          date_end: '2015-12-31'
    design:
      columns: '2'
  - block: markdown
    id: teaching
    content:
      title: Teaching
      text: "**Clinical Assistant Professor, NYU, Fall 2018 - present**

- MATH-UA 009 Algebra and Calculus: Fall 2019, Fall 2021

- MATH-UA 121 Calculus I: Spring 2020, Spring 2021, Fall 2022, Spring 2023

- MATH-UA 122 Calculus II: Fall 2018, Fall 2020, Fall 2021

- MATH-UA 123 Calculus III: Fall 2020, Spring 2021, Spring 2022, Fall 2022

- MATH-UA 140 Linear Algebra: Spring 2019, Fall 2019, Spring 2020, Spring 2022

- CORE-UA 105 Elementary Statistics: Fall 2018, Spring 2019, Spring 2022

- MG-GY 6193 Statistics for Data Analysts (graduate): Spring 2022

- HEOP-UE 601 Pre-First Year Calculus: Summer 2021, Summer 2022

- HEOP-UE 610 Pre-Freshman Pre-Calculus: Summer 2021

- CMT- NA 100 Graph Theory: Summer 2022


**Adjunct Instructor, NYU, Fall 2014 - Summer 2018**

- MA-UY 2224 Data Analysis, Summer 2018

- MA-UY 2054 Applied Business Data Analysis I, Spring 2018

- MA-UY 914 Precalculus for Engineers, Fall 2017

- MA-UY 2414 Basic Practice of Statistics for Social Science, Spring 2016

- MA-UY 914 Precalculus for Engineers, Fall 2015

- MA-UY 2414 Basic Practice of Statistics for Social Science, Spring 2015

- MA-UY 914 Precalculus for Engineers, Fall 2014


**Focused Recitation/Math Workshop Instructor, NYU, Fall 2014 - present**

- Subjects: Calculus I, Calculus II, Data Analysis, Linear Algebra & Differential Equation, Introduction to Probability

<br>

#### View my online teaching evaluation at [Rate My Professor](http://www.ratemyprofessors.com/ShowRatings.jsp?tid=1966958)


Or contact me for my NYU internal course evaluation reports"
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
  - block: markdown
    id: advising
    content:
      title: Students Advising
      text: "
     +  **Deans' Undergraduate Research Fund (DURF)**: Vaisnav Gajaraj (2018, 2019), Celia Xie (2019), Tina Xu (2019), Derek Huang (2020), Baron Guo (2022), Yiming Bian (2022)

     -  **Summer Undergradute Research Experience**: Jiayi Ji (2021), Yijie Wang (2021), Hui Wen Goh (2022), Lu yii Wong (2022)

     + **Vertically Integrated Projects (VIP)**: Bing Yang Tan (2022), Vikram Sagi (2022)

     -  Shizhu is the **NYU SIAM Chapter** faculty advisor, if you are interested in events organized by NYU SIAM or you would like to join the team, please visit [their webiste](https://nyusiam.org/people/) or email Shizhu.


"
    design:
      columns: '2'
  - block: markdown
    id: modeling
    content:
      title: Math Modeling
      text: "
      Shizhu is the host for **NYU Undergraduate Math Modeling Workshop**. 
      
      
      This workshop is an informal weekly seminar sessions for all NYU undergraduate students who are interested in learning more about mathematical modeling. The workshops started out as a way to help prepare students who are interested in participating in the Mathematical/Interdisciplinary Contest in Modeling (MCM/ICM), an annual international competition where teams of undergraduates use mathematical modeling approaches to propose solutions to real world problems. 


      If you are interested in this workshop or/and the contests and if you would like to be included in the workshop brightspace site, please vist [the website](https://sites.google.com/nyu.edu/mathmodeling/home) (log in using your NYU credential).
      "
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      email: shizhu.liu@courant.nyu.edu
      appointment_url: 'https://shizhuliu.youcanbook.me'
      address:
        street: 251 Mercer St
        city: New York
        region: NY
        postcode: '10012'
        country: United States
        country_code: US
      directions: Warren Weaver Hall (WWH), Office 720
      # office_hours:
      #   - 'Monday 10:00 to 13:00'
      #   - 'Wednesday 09:00 to 10:00'
      # Automatically link email and phone or display as text?
      autolink: True
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: true
    design:
      columns: '2'
---
