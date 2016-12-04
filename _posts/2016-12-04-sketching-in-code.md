---
layout: default
title: What is sketching in code?
description: Sketching in code is where you prototype your ideas in code as soon as possible.
read_time: 8 minute
---

<p class="abstract">Sketching in code is where you prototype your ideas in code as soon as possible.</p>

Prototyping is an important part of the design process. It lets you test your ideas and understand some of the constraints you may have to face.

> Ideas are cheap, actually making stuff is where you begin to win the battle.

The most important part about prototyping is that it takes an idea or hypothesis and demonstrates how you plan to address it. It makes sure that your idea(or your team’s idea) is valid. It and makes it easy for others to have a shared understanding of what you are trying to do.

## Why you should be sketching in code

Sketching in code solves the issues encountered when prototyping in tools such as Photoshop, Invision or Axure. It means that developers are invaluable team members during the design process.

I’ve been working in agile, multidisciplinary teams sketching in code for some time now. Here are the major benefits our teams have noticed:

### Design within the constraints of browser technology

The main constraints I encounter when designing for the web are:

- #### Accessibility

  Sketching in code forces you to understand how you are structuring the HTML on your page. It makes it much easier to understand the accessibility issues you need to solve. I prefer to structure the HTML on the page before designing the page layout.

- #### Understand the simplest way to solve a problem

  Many problems can be solved using existing frameworks or libraries. If you start by finding the simplest solution in code first it can save time from building bespoke functionality.

- #### Responsive design

  It is much easier to understand how your page layouts respond when designing in the browser. It is hard to address these constraints if you are designing and building your prototype in anything other than code.

Sketching in code highlights these issues to the team and lets you address them early and often.

### Easy to share

Having a codified prototype means that you can host your prototype on the web. This means that:

- All your team can see the latest version of the prototype
- If you version control code it’s easy to have history of the prototype
- Showing people a real thing on their real device is magical
- Easy to test

### Easy to test

A critical part of the prototyping design process is testing the prototype with users. This is how we get feedback about whether our ideas are valid. Sketching in code will allow you to:

- test your prototype on a real device(or their own device)
- test your prototype across mobile and desktop.
- test with remote users.
- add analytics or screen record user interactions
- test with people who use assistive technology. This includes [users with diverse abilities](https://www.w3.org/WAI/intro/people-use-web/diversity) such as:
  - vision impairment
  - mobility impairment
  - age related impairment

## How to do it

The outcome of prototyping is to:

- Define a clear and shared understanding of what you are going to build
- Confirm your original idea or hypothesis is valid

It is important to remember that prototyping shouldn't be the same as building production software. It's about rapidly testing and validating ideas before committing to building production software.

I recommend the following guidelines for prototyping.

### Don’t waste time on code quality

The goal is to test your ideas, not build production ready code. Evaluate whether you need to support older browsers. Your team will be much more effective if they are focused on building and testing ideas, not writing fallbacks for IE7 or refactoring code.

### Keep the tech simple

Evaluate how you want to build the prototype. Remember that the most important thing is to be able to build ideas out quickly. Some ideas you build will get disproved and you will have to delete them anyway. I personally use static site generators for prototyping such as Jekyll. If you have a developer that is more comfortable using a javascript framework then use that. If you prefer using a CMS like Wordpress, then use that.

### Fake it if you can

Evaluate whether you need to integrate with existing services or real data. I recommend avoiding trying to use or integrate with real data. It’s much simpler to fake interactions with JavaScript than to integrate with production systems. You need to decide whether it is possible to test your ideas without using real data.

### Make it easy for everyone to contribute

Try to make it easy for non-technical people in the team to contribute to the prototype. While this isn’t critical it’s always better to harness the collective intelligence of the team. We should remove the developers as blockers for ideas getting into the prototype. This may be showing your team mates how to edit markdown files in GitHub, or editing a JSON blob consumed by your prototype.

## Next steps

I am planning to write another article explaining how I setup the technology for rapid prototyping. Stay tuned.

## Acknowledgements

I wrote this article to capture the things I have learnt while working at the Digital Transformation Agency(DTA). The DTA have also published some information about the design process and sketching in code:

- [Digital Service Standard](https://www.dta.gov.au/standard/)
- [Service handbook](http://ausdto.github.io/service-handbook/alpha/3-building-prototypes/3-1-what-is-prototype.html)
