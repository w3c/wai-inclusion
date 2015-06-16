---
title: Web for All
subtitle: Accessibility, Usability, and Inclusion
status: editors-draft
editors:
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

The Web is fundamentally designed to work for all people, whatever their hardware, software, language, culture, location, or physical or mental ability. According to Tim Berners-Lee, W3C Director and inventor of the World Wide Web, "The power of the Web is in its universality"

Several complementary efforts are necessary to achieve this goal of a universal web. For example, technical foundations so that the Web is supported across devices and operating systems, and design practices so that the Web is usable by everyone. Thus the terms *accessibility, usability, and inclusion* are closely related and overlap significantly. It is most effective to address them together in many situations, such as when developing websites. There are a few cases when it is important to distinguish between these terms, such as when defining specific requirements and standards.

**The purpose of this document is to encourage increased communication and coordination between accessibility and usability research and practice** in the design and development of guidelines, websites, browsers, assistive technologies, and other web tools to make them accessible, inclusive, and usable for everyone.

## Understanding Accessibility

Accessibility is about ensuring an equivalent user experience for people with disabilities, including people with age-related impairments. For the Web, accessibility means that people with disabilities can perceive, understand, navigate, and interact with websites and tools, and that they can contribute equally without barriers. Access to information and communications technologies is a basic human right as recognized in the [UN Convention on the Rights of Persons with Disabilities (CRPD)](http://www.un.org/disabilities/default.asp?navid=12&pid=150). See [Accessibility - W3C](/standards/webdesign/accessibility) for an introduction to web accessibility.

Most accessibility guidelines also [improve usability for everyone](/WAI/bcase/fin.html#increase-use), and especially benefit [older users](/WAI/older-users/), [people using different devices](/WAI/mobile/), and [others such as](/WAI/bcase/soc#groups) people with low literacy or not fluent in the language, and people with low bandwidth connections or using older technologies. Thus accessibility includes both:

* Requirements that are more specific to people with disabilities; for example, they ensure that websites work well with assistive technologies such as screen readers that read aloud web pages, screen magnifiers that enlarge web pages, and voice recognition software that is used to input text. Most of these requirements are technical and relate to the underlying code rather than to the visual appearance.
* Requirements that are also general usability principles, which are included in accessibility requirements because they can be significant barriers to people with disabilities. For example, a website that is developed so that it can be used without a mouse is good usability; and use without a mouse is an accessibility requirement because people with some physical and visual disabilities cannot use a mouse at all.

Websites, web tools, and other products that meet accessibility goals are more usable for everyone.

## Understanding Inclusion

Inclusion is about ensuring access for everyone, and that nobody is left behind. This includes people with low computer skills, literacy, or not fluent in the language, and people with low bandwidth connections or using older technologies. While accessibility addresses some of these aspects, it does not address them fully given its focus on people with disabilities. For example, accessibility addresses requirements for older people related to functional limitations but may not address all aspects related to digital literacy, which are frequently an issue among older people.

The inter-relationships between the different user groups are very close, and addressing one user group usually benefits others. For example, affordability of computer technology is critical for people with low income, which includes many people with disabilities. @@@ need to have focus groups to develop complementary solutions @@@

## Understanding Usability and User-Centered Design (UCD)

Usability is about designing products to be effective, efficient, and satisfying. Usability is part of the human-computer interaction (HCI) research and design field (which is much broader than usability testing). For web developers, a key aspect of usability is following a user-centered design (UCD) process to create positive user experiences.

User-centered design (UCD) focuses on usability goals, user characteristics, environment, tasks, and workflow in designing a user interface to meet user requirements. For example, UCD considers users' hardware, software, computer experience, task knowledge, and other characteristics in designing a website, web application, browser, and other web tool. UCD is an iterative process with well-defined methods and techniques for analysis, design, and evaluation from the first stage of projects through implementation.

{:.no_toc}
### Including Accessibility in Usability Research and Practice

Usability efforts often focus on primary user groups and common user characteristics; in the past, many have not included people with disabilities. More and more usability specialists are recognizing the benefits of including people with disabilities in usability research and practice, including:


* Involving people with disabilities early in design processes broadens designers' perspectives and can lead to making products work better for more people in more situations.
* Involving participants with disabilities in evaluation can identify usability issues more easily because people with disabilities are often more sensitive to usability problems. For example, a large number of links poorly organized on a web page will be more of a problem for people with some types of cognitive, physical, or visual disabilities.
* Including accessibility guidelines throughout the design process helps improves usability for people with and without disabilities.

[Involving Users in Web Projects for Better, Easier Accessibility](/WAI/users/involving) introduces some basics. [Just Ask: Integrating Accessibility Throughout Design](http://www.uiaccess.com/accessucd/overview.html) provides detailed guidance on incorporating accessibility in user-centered design.

## Usable Accessibility - Including Usability in Accessibility Research and Practice

Usable accessibility combines usability and accessibility to develop positive user experiences for people with disabilities. User-centered design processes (UCD) include both techniques for including users throughout design and evaluation, and using guidelines for design and evaluation. UCD helps make informed decisions about accessible design. Thus UCD is necessary to improve accessibility in websites and web tools.

{:.no_toc}
### Real People

The goal of web accessibility is to make the Web work well for people, specifically people with disabilities. While technical standards are an essential tool for meeting that goal, marking off a checklist is not the end goal. **People with disabilities effectively interacting with and contributing to the Web is the end goal.**

To make the Web work well for people with disabilities, designers and developers need to understand the basics of [how people with disabilities use the Web](/WAI/intro/people-use-web). Following UCD to [involve people with disabilities throughout design processes](/WAI/users/involving) and [involve users in web accessibility evaluation](/WAI/eval/users) helps design solutions that are effective for users and for developers. (See also: [How Involving Users Early Helps section](/WAI/users/involving#why).)

{:.no_toc}
### Technical Standards

While including users with disabilities is key to making accessibility efforts more effective and more efficient, that alone cannot address all issues. Even large projects cannot cover the diversity of disabilities, adaptive strategies, and assistive technologies. That is the role of accessibility standards.

The W3C Web Accessibility Initiative (WAI) [develops](/WAI/intro/w3c-process) a [set of guidelines](/WAI/guid-tech.html) that are internationally recognized as the standard for web accessibility. These WAI guidelines include considerations for people with auditory, cognitive, neurological, physical, speech, and visual disabilities, including people with age-related impairments.

The WAI guidelines are stable technical standards for meeting user requirements that apply broadly across technologies and situations. Along with the guidelines are techniques and other supporting resources that provide details on how to meet the guidelines (and thus the user requirements) in specific situations.

## Working Together with Accessibility

There are efforts to make the Web and other technology available to and usable by all people whatever their abilities, age, economic situation, education, geographic location, language, etc. *Digital inclusion, design for all, universal usability*, and similar efforts address the broad range of issues; whereas accessibility focuses specifically on people with disabilities, including people with age-related impairments. Often projects address one user group; for example, developing design guidelines to optimize websites for older users. Many of the requirements of different user groups overlap with the requirements of people with disabilities.

**Coordinating related efforts with existing accessibility work supports [international harmonization and interoperability](/WAI/Policy/harmon), and can expand research and resources in both areas.** However, when efforts are not coordinated, it leads to duplication of effort and confusing or even conflicting results. For example, an extensive [literature review on web accessibility for older users](/WAI/intro/wai-age-literature) showed that most research and development of web design recommendations for older users did not consider WAI guidelines at all, even though the WAI guidelines directly address the accessibility needs of older web users.

When researchers, designers, and developers, and others are developing web design guidelines, they might identify different kinds of issues:

* **Issues that affect people with disabilities disproportionately** - These are considered accessibility barriers and need to be addressed by the WAI guidelines. For example, clear navigation mechanisms help everyone yet unclear navigation mechanisms can be particularly confusing for people with visual and cognitive disabilities. **WAI welcomes comments on existing standards**. New findings can be addressed through the techniques or other supporting documents, included in errata, and/or incorporated in future developments of standards.
* **Particular combinations of independent design issues that create accessibility barriers** - For example, needing to change settings that are difficult to find in common browsers, such as text size and color settings, is an obstacle for many users, including people with disabilities. In this case, the browser could be improved to help users customize the settings and the website could be improved to help educate users on how to customize their browsers. **WAI welcomes the contribution of additional techniques**, including techniques that help address accessibility issues in specific design situations and tools.
* **Issues that are not specifically related to people with disabilities** - For example, lack of computer skills is a common issue for some older users, people with lower income, people in less developed areas, and others. Even though such issues are not considered accessibility barriers specifically for people with disabilities and thus are not directly covered in accessibility guidelines, they may be related to accessibility issues that are covered. Therefore, **design guidelines for such issues should build on existing accessibility guidelines**, to take advantage of existing work and ensure harmonization.

{:.no_toc}
### Coordinating with WAI

W3C Web Accessibility Initiative (WAI) provides an international forum for collaboration between industry, disability organizations, accessibility researchers, government, and others interested in web accessibility. WAI encourages those involved in usability, digital inclusion, and others to share perspectives and [participate in WAI work](/WAI/participation).

* The WAI Interest Group (IG) is open for anyone to read or share feedback, comments, research findings, and questions related to web accessibility.
* The e-mail address for all [WAI staff](/People/domain?domain=Web+Accessibility+Initiative) is [wai@w3.org](mailto:wai@w3.org).
* To contribute to WCAG, see [instructions for commenting on WCAG 2.0 documents](/WAI/WCAG20/comments/) and the [form for submitting WCAG 2.0 techniques](/WAI/GL/WCAG20/TECHS-SUBMIT/).
* [Participating in WAI](/WAI/participation) describes opportunities ranging from volunteering to implement, promote, and review guidelines, to occasional participation in an interest group, to dedicated participation in a working group.

WAI looks forward to increased collaboration among usability, digital inclusion, and accessibility research and practice.