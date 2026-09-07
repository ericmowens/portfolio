---
date: '2021-05-01T00:00:00+01:00'
title: 'Octopart Datasheet Subdomain'
draft: false

params:
    button:
        icon: "icon-arrow-right"
        btnText: "Example Site"
        URL: "https://octopart.com/datasheet/stmicroelectronics/TDA7269A"
    image:
        src: "images/works/octopart.png"
        scale: 0.5

## The content is used for the description of the project
---

Octopart is essentially a search engine for electronic parts. During my internship at Octopart, my main project was implementing the /datasheet/ subdomain of the website. For eligible electronic parts listed on their site, a pdf of the part's datasheet will be directly accessible, keeping users on the site. I implemented this solution using React, Next.js and Node to ensure a stable experience across devices. My changes were deployed using Docker and pushed to the live site using AWS and Jenkins. This subdomain has been live on the site for years now.