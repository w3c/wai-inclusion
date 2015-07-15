---
title: Web for All
subtitle: Accessibility, Usability, and Inclusion
status: editors-draft
editors:
  - Kevin White
  - Shawn Lawton Henry
  - Shadi Abou-Zahra
contributors:
  - participants of the <a href="/WAI/EO/2008/wai-age-tf.html#participants">WAI-AGE Task Force</a>
  - the <a href="/WAI/EO/">Education and Outreach Working Group (EOWG)</a>
---

{::nomarkdown}
<%= page_contents %>
{:/}

{:toc}
* Will be replaced with the ToC

{::nomarkdown}
<%= page_contents :end %>
{:/}

## Introduction

The Web is fundamentally designed to work for all people, whatever their hardware, software, language, culture, location, or physical or mental ability.

> "The power of the Web is in its universality"
  <cite>- Time Berners-Lee, W3C Director and inventor of the World Wide Web</cite>

A universal web depends on several complementary efforts. For example, technical foundations to ensure support across devices and operating systems, and design practices to help make interfaces widely usable.

*Accessibility, usability, and inclusion* are three activities that are closely related and overlap significantly. They are often more effectively addressed together, such as when developing websites. There are a few cases when it is important to distinguish between these terms, such as when defining specific requirements and standards.

**The purpose of this document is to encourage increased communication and coordination between accessibility, usability, and inclusion research and practice** in the design and development of guidelines, websites, browsers, assistive technologies, and other web tools to make them accessible, inclusive, and usable for everyone.

## Understanding Accessibility

Accessibility is concerned with ensuring an equivalent user experience for people with disabilities, including people with age-related impairments. For the Web, accessibility means that people with disabilities can perceive, understand, navigate, and interact with websites and tools, and that they can contribute equally without barriers. Access to information and communications technologies is a basic human right as recognized in the [UN Convention on the Rights of Persons with Disabilities (CRPD)](http://www.un.org/disabilities/default.asp?navid=12&pid=150). The <acronym title="World Wide Web Consortium">W3C</acronym> provides an [introduction to web accessibility](/standards/webdesign/accessibility).

Accessibility also [improves usability for everyone](/WAI/bcase/fin.html#usability), and especially benefits [older users](/WAI/older-users/), [people using different devices](/WAI/mobile/), and others, such as [people with low literacy or not fluent in the language](/WAI/bcase/soc#lolit), and [people with low bandwidth connections or using older technologies](/WAI/bcase/soc#lowtech). Accessibility includes:

* Requirements that are more specific to people with disabilities

  For example, technical requirements that help ensure websites work well with assistive technologies such as screen readers that read aloud web pages, screen magnifiers that enlarge web pages, and voice recognition software that is used to input text.

* Requirements that benefit all users

  For example, high color contrast for text might be necessary for some people with disabilities to be able to read the text, but it will also benefit other people by making the text more legible.

Websites and services that meet accessibility goals are more usable for everyone.

## Understanding Inclusion

Inclusion is concerned with ensuring access for everyone, and that nobody is left behind. As well as people with disabilities, this also includes people with low computer skills, literacy, or not fluent in the language, and people with low bandwidth connections or using older technologies. While accessibility addresses some of these aspects, it does not address them fully given its focus on people with disabilities. For example, accessibility addresses requirements for older people related to functional limitations but may not address all aspects related to digital literacy, which are frequently an issue among older people.

The needs of different user groups are closely inter-related, and addressing one user group usually benefits others. For example, affordability of computer technology is critical for people with low income, which includes many people with disabilities. <span style="background: yellow">@@@ need to have focus groups to develop complementary solutions @@@</span>

## Understanding Usability

Usability is about designing products to be effective, efficient, and satisfying. Usability is part of the human-computer interaction (HCI) research and design field. For web developers, a key aspect of usability is following a user-centered design (UCD) process to create positive user experiences.

<acronym title="User-centered design">UCD</acronym> focuses on usability goals, user characteristics, environment, tasks, and workflow in designing a user interface to meet user requirements. For example, <acronym title="User-centered design">UCD</acronym> considers users' hardware, software, computer experience, task knowledge, and other characteristics in designing a website or service. <acronym title="User-centered design">UCD</acronym> is an iterative process with well-defined methods and techniques for analysis, design, and evaluation from the first stage of projects through implementation.

## Expanded Usability Research

Usability efforts often focus on primary user groups and common user characteristics; in the past, many have not included people with disabilities. However, there are benefits to including people with disabilities in usability research and practice, including:

* **Broader design perspectives**

  Involving people with disabilities early in design processes broadens designers' perspectives and can lead to making products work better for more people in more situations.

* **Easier identification of usability issues**

  People with disabilities are often more sensitive to usability problems, making the problems much more apparent. For example, a large number of links poorly organized on a web page will be more of a problem for people with some types of cognitive, physical, or visual disabilities.
  
* <span style="background: yellow">Including accessibility guidelines throughout the design process helps improve usability for people with and without disabilities.</span>

[Involving Users in Web Projects for Better, Easier Accessibility](/WAI/users/involving) introduces some basics. [Just Ask: Integrating Accessibility Throughout Design](http://www.uiaccess.com/accessucd/overview.html) provides detailed guidance on incorporating accessibility in user-centered design.

{:.no_toc}
### Accessibility and User Research

The needs of people with disabilities can be incorporated into a number of user research activities. For example:

* **Usability Testing**

  A staple research methodology that will benefit from including people with disabilities. Early stage prototypes might not be usable by assistive technology users, but more complete websites should not present such problems. People with disabilities provide insight both as potential users of the web service and into any accessibility issues.

* **Persona development**

  [Personas](http://www.usability.gov/how-to-and-tools/methods/personas.html) are a valuable tool in understanding and communicating user needs. Including personas with disabilities will highlight the importance of this audience and allow for common barriers to be communicated across the project team.
  
* **Use Cases**

  [Use Cases](http://www.usability.gov/how-to-and-tools/methods/use-cases.html) explain how a user engages with a website and how the system responds. Incorporating use cases for common tasks performed by users with disabilities will help highlight where potential issues will arise.  

* **Prototype development**

  Prototypes are often not supportive of assistive technology. Where design choices are likely to cause accessibility barriers, for example, including carousels or modal pop-ups, notes on how to avoid these barriers can be included with the prototype. 

{:.no_toc}
### Inclusion and User Research

Where target audiences are broad, such as government sites that cover large populations, then inclusion is particularly important. As with accessibility, user research methods can be adapted to incorporate broader audience needs.

When responding to particular web product goals, such as responsive design for better mobile delivery, there are often added inclusive benefits, in this case better presentation for users with poor eyesight who use browser zoom. Benefits from accessibility modifications often make websites more inclusive as well, for example adding captions and transcripts to multimedia are an accessibility requirement that make it easier for non-native language speakers to use the material.

## Usable Accessibility

Accessibility is more than just usability for people with disabilities. However, <acronym title="User-centered design">UCD</acronym> methods and approaches can bring significant value to researching accessible solutions and improving websites and services. Accessibility is often considered only from the perspective of the technical standards, which may be appropriate, for example, when seeking to define legislation. Usability seeks to engage with real people in order to shape products and help make informed design decisions.

In reality both technical standards and input from real people are important when designing and developing accessible web solutions.

{:.no_toc}
### Real People

The goal of web accessibility is to make the Web work well for people, specifically people with disabilities. While technical standards are an essential tool for meeting that goal, marking off a checklist is not the end goal. People with disabilities effectively interacting with and contributing to the Web is the end goal.

To make the Web work well for people with disabilities, all those involved in creating websites need to understand the basics of [how people with disabilities use the Web](/WAI/intro/people-use-web). Following <acronym title="User-centered design">UCD</acronym> recommends that [people with disabilities are involved](/WAI/users/involving) throughout the design process, ideally [early in the design process](/WAI/users/involving#why), and [in web accessibility evaluations](/WAI/eval/users). This approach helps to design solutions that are effective for users with disabilities and provides additional benefits to all other users.

{:.no_toc}
### Technical Standards

While including users with disabilities is key to making accessibility efforts more effective and more efficient, that alone cannot address all issues. Even large projects cannot cover the diversity of disabilities, adaptive strategies, and assistive technologies. That is the role of accessibility standards.

The W3C Web Accessibility Initiative (WAI) develops a [set of guidelines](/WAI/guid-tech.html) that are internationally recognized as the standard for web accessibility. These <acronym title="Web Accessibility Initiative">WAI</acronym> guidelines include considerations for people with auditory, cognitive, neurological, physical, speech, and visual disabilities, including people with age-related impairments.

The <acronym title="Web Accessibility Initiative">WAI</acronym> guidelines are stable technical standards for meeting user requirements that apply broadly across technologies and situations. Along with the guidelines are techniques and other supporting resources that provide details on how to meet the guidelines, and thus the user requirements, in specific situations.