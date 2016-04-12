---
title: Accessibility, Usability, and Inclusion
subtitle: Understanding How to Implement a Web for All
status: editors-draft
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

*Accessibility, usability, and inclusion* are three activities that are closely related and overlap significantly. There are a few cases when it is important to distinguish between these terms, such as when defining specific requirements and standards. However, they aremore effectively addressed together, such as when designing and developing websites and applications. A holistic approach, with understanding for the different requirements and standards, leads to a more accessible, usable, and inclusive web for everyone.

## Background

The needs of different user groups are closely inter-related, and addressing one user group usually benefits others. For example, affordability of computer technology is critical for people with low income, which includes many people with disabilities. Yet in some cases, such as for the design of requirements and standards, it is important to have detailed expertise in the particular areas to ensure adequate coverage. For example, affordability can have additional repercussions due to the particular type of disability, such as the need for assistive technology, broadband, or particular hardware and software. There is a need for expertise within the different user groups, and a need for such experts to work together.

{:.no_toc}
### Understanding Accessibility

Accessibility is concerned with ensuring an equivalent user experience for people with disabilities, including people with age-related impairments. For the Web, accessibility means that people with disabilities can perceive, understand, navigate, and interact with websites and tools, and that they can contribute equally without barriers. Further background is provided in the [introduction to web accessibility](/standards/webdesign/accessibility).

{:.no_toc}
### Understanding Usability

Usability is about designing products to be effective, efficient, and satisfying for the target audience of the product. If the target audience is correctly defined to also include people with disabilities, then the relationship between accessibility and usability becomes immediate. However, generally usability has a broader focus on the entirety of all target audience, and not specifically on issues that disproportionately impact people with disabilities. For example, a more usable website could be more appealing to everyone regardless of disability, whereas a more accessible website could be more appealing to people with disabilities without necessarily improving the user experience for all other audiences. In most cases though, addressing one aspect also benefits the other, which is why they are best approached together.

{:.no_toc}
### Understanding Inclusion

Inclusion is concerned with ensuring access for everyone, and that nobody is left behind. As well as people with disabilities, this also includes people with low computer skills, literacy, or not fluent in the language, and people with low bandwidth connections or using older technologies. While accessibility addresses some of these aspects, it does not address them fully given its focus on people with disabilities. For example, accessibility addresses requirements for older people related to functional limitations but may not address all aspects related to digital literacy, which are frequently an issue among older people too.

## Design for Inclusion

In some regions this is referred to as *universal design, inclusive design, or design for all*. It involves designing products, such as websites, to allow their use by the broadest audience possible. This includes people with different needs and preferences, which may be seemingly compatible or conflicting. For example, one person may need text size larger or smaller than another, or may prefer a specific font type over another. This may be due to disability or other circumstance. Fortunately the Web is designed to be adaptable so that it can meet the different needs. However, web designers and developers need to make appropriate considerations to ensure this promise. [How People with Disabilities Use the Web](http://www.w3.org/WAI/intro/people-use-web/) provides an overview on accessibility considerations.

## Accessible Design

Part of designing for inclusion is to ensure an accessible design. Web accessibility is supported by a comprehensive set of [guidelines, standards, and techniques](https://www.w3.org/WAI/guid-tech.html) to support the design and development of websites and applications, including on mobile and other devices; web browsers and media players; and authoring tools such as content management systems (CMS). These can be combined with other standards and techniques, such as for [internationalization](https://www.w3.org/International/). Usability provides complementary methods and processes, such as the user-centered design (UCD) process, to help implement such technical standards effectively.

{:.no_toc}
### Usable Accessibility

In reality both technical standards and input from real people are important when designing and developing accessible web solutions. For web designers and developers, a key aspect of usability is following a user-centered design (UCD) process to create positive user experiences. <abbr>UCD</abbr> focuses on usability goals, user characteristics, environment, tasks, and workflow in designing a user interface to meet user requirements. For example, <abbr>UCD</abbr> considers users' hardware, software, computer experience, task knowledge, and other characteristics in designing a website or service. <abbr>UCD</abbr> is an iterative process with well-defined methods and techniques for analysis, design, and evaluation from the first stage of projects through implementation. The needs of people with disabilities can be incorporated throughout the process; for example:

* *Usability Testing* - A staple research methodology that will benefit from including people with disabilities. Early stage prototypes might not be usable by assistive technology users, but more complete websites should not present such problems. People with disabilities provide insight both as potential users of the web service and into any accessibility issues.

* *Persona development* - Personas are a valuable tool in understanding and communicating user needs. Including personas with disabilities will highlight the importance of this audience and allow for common barriers to be communicated across the project team.
  
* *Use Cases* - Use Cases explain how a user engages with a website and how the system responds. Incorporating use cases for common tasks performed by users with disabilities will help highlight where potential issues will arise.  

* *Prototype development* - Prototypes are often not supportive of assistive technology. Where design choices are likely to cause accessibility barriers, for example, including carousels or modal pop-ups, notes on how to avoid these barriers can be included with the prototype. 

* *Technical Standards* - While including users with disabilities is key to making accessibility efforts more effective and more efficient, that alone cannot address all issues. Even large projects cannot cover the diversity of disabilities, adaptive strategies, and assistive technologies. That is the role of accessibility standards.

{:.no_toc}
### Real People

The goal of web accessibility is to make the Web work well for people, specifically people with disabilities. While technical standards are an essential tool for meeting that goal, marking off a checklist is not the end goal. People with disabilities effectively interacting with and contributing to the Web is the end goal.

To make the Web work well for people with disabilities, all those involved in creating websites need to understand the basics of [how people with disabilities use the Web](/WAI/intro/people-use-web). Following <abbr>UCD</abbr> recommends that [people with disabilities are involved](/WAI/users/involving) throughout the design process, ideally [early in the design process](/WAI/users/involving#why), and [in web accessibility evaluations](/WAI/eval/users). This approach helps to design solutions that are effective for users with disabilities and provides additional benefits to all other users.

Usability efforts often focus on primary user groups and common user characteristics; in the past, many have not included people with disabilities. However, there are benefits to including people with disabilities in usability research and practice, including:

* *Broader design perspectives* - Involving people with disabilities early in design processes broadens designers' perspectives and can lead to making products work better for more people in more situations.

* *Easier identification of usability issues* - People with disabilities are often more sensitive to usability problems, making the problems much more apparent. For example, a large number of links poorly organized on a web page will be more of a problem for people with some types of cognitive, physical, or visual disabilities.
