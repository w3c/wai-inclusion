---
layout: default
title: Accessibility, Usability, and Inclusion
permalink: /fundamentals/accessibility-usability-inclusion/
status: editors-draft
date: 2016-12-15
people:
  editorslabel: "Editor"
  editors:
    - name: Shadi Abou-Zahra
      url: https://www.w3.org/People/shadi
    - name: Shawn Lawton Henry
      url: https://www.w3.org/People/Shawn
    - name: Kevin White
      url: https://www.w3.org/People/kevin
  contributors:
    - name: Sharron Rush
support:
  - name: WAI-DEV Project
    url: https://www.w3.org/WAI/WAI-DEV/
  - name: WAI-AGE Project
    url: https://www.w3.org/WAI/WAI-AGE/
---

Introduction
------------
{:#introduction.no-display}

*Accessibility, usability, and inclusion* are closely related aspects in
creating a web that works for everyone. Their goals, approaches, and
guidelines overlap significantly. When designing and developing websites
and applications, it is most effective to address them together.

There are a few situations when it's important to focus specifically on
one aspect, such as when researching accessibility needs of people with
disabilities to help develop standards and policies.

This article briefly:

-   explains the distinctions and overlaps between accessibility,
    usability, and inclusive design,
-   encourages increased coordination across research and practice in
    these disciplines, and,
-   points out the importance of maintaining the focus of accessibility
    on people with disabilities.

Distinctions and Overlaps {#terms}
-------------------------

**Accessibility**
:   *Accessibility* addresses discriminatory aspects related to
    equivalent user experience for people with disabilities. For the
    web, accessibility means that people with disabilities can equally
    perceive, understand, navigate, and interact with websites and
    tools, and that they can contribute equally without barriers. For
    more information, see the [Accessibility
    introduction]({{ site.github.url }}/fundamentals/accessibility-intro/).

**Usability**
:   *Usability*, including *user experience design*, is about designing
    products to be effective, efficient, and satisfying. This may
    include general aspects that impact everyone and do not
    disproportionally impact people with disabilities. Moreover, the
    needs of people with disabilities are often not sufficiently
    addressed in usability practice and research.

**Inclusion**
:   *Inclusion*, also *universal design* and *design for all*, is about
    ensuring involvement of everyone to the greatest extent possible. It
    addresses a broad range of issues including access to and quality of
    hardware, software, and Internet connectivity; computer literacy and
    skills; economic situation; education; geographic location; age; and
    language — as well as disability.

### Accessibility and Usability {#accessible-usable}

While accessibility focuses on people with disabilities, many
accessibility requirements also improve usability for everyone. For
example, accessibility features such as providing sufficient contrast,
scalable font size, and captioning also benefit people in limiting
situations, such as using the web on a mobile phone when visual
attention is elsewhere, in bright sunlight, in a dark room, and in quiet
or noisy environments. Accessibility also addresses functional
limitations aquired by age, even though some people may not identify
these as "disability".

Accessibility includes:

-   **Requirements that are technical and relate to the underlying code
    rather than to the visual appearance** — for example, they ensure
    that websites work well with assistive technologies such as screen
    readers that read aloud web pages, screen magnifiers that enlarge
    web pages, and voice recognition software that is used to input
    text. These aspects are typically not a focus of usability research
    and practice.
-   **Requirements that relate to user interaction and visual design** —
    they are included in accessibility requirements because they can be
    significant barriers to people with disabilities. For example,
    understandable instructions and feedback for website forms and
    applications is good usability; and is also an accessibility
    requirement because many people with cognitive and learning
    disabilities are otherwise excluded.

Thus accessibility and usability overlap significantly. According to
[ISO
9241-11](http://www.iso.org/iso/catalogue_detail.htm?csnumber=16883),
usability is defined as the "extent to which a product can be used by
specified users to achieve specified goals effectively, efficiently and
with satisfaction in a specified context of use". This could address
accessibility ***when*** "specified users" includes people with a range
of disabilities and "specified context of use" includes accessibility
considerations such as assistive technologies. However, the needs of
people with disabilities are often not sufficiently addressed in
usability practice and research.

### Accessibility and Inclusion {#inclusive-design}

Several accessibility requirements also benefit people and situations
that are a focus of inclusive design. For example, [Web Accessibility
Benefits People With
and *Without* Disabilities](https://www.w3.org/WAI/bcase/soc#groups)
describes accessibility benefits for:

-   people with low literacy or not fluent in the language,
-   people with low bandwidth connections or using older technologies,
-   new and infrequent users, and,
-   [mobile device users](https://www.w3.org/WAI/mobile/overlap).

However, accessibility focuses on disability and does not try to address
broader issues. Other efforts, such as
[internationalization](https://www.w3.org/International/), address other
inclusion issues. Keeping accessibility focused on disabilities
encourages research and development on the specific needs of people with
disabilities, and solutions that are optimized for these specific needs.

Accessible Design
-----------------

There are [guidelines, standards, and techniques for web
accessibility](https://www.w3.org/WAI/guid-tech.html), such as the Web
Content Accessibility Guidelines
([WCAG](http://www.w3.org/WAI/intro/wcag)), which is the international
standard [ISO/IEC
40500](https://www.w3.org/blog/2012/10/wcag-20-is-now-also-isoiec-405/).
Yet when designers, developers, and project managers approach
accessibility as a checklist to meet these standards, the focus is only
on the technical aspects of accessibility. As a result, the human
interaction aspect is often lost, and accessibility is not achieved.

Combining accessibility standards and usability processes with real
people ensures that web design is technically and functionally usable by
people with disabilities. This is referred to as *usable accessibility*
or *accessible user experience (UX)*.

### Usable Accessibility

Web designers and developers can use usability processes, methods, and
techniques, to address the user interface component of accessibility.
While the considerations of people with disabilities are not always
included in common practices, they can be easily integrated into user
experience design.

A key aspect is incorporating **real people** in design:

-   Ensuring that everyone involved in web projects understands the
    basics of [how people with disabilities use the
    Web](https://www.w3.org/WAI/intro/people-use-web),
-   [Involving users with
    disabilities](https://www.w3.org/WAI/users/involving) early and
    throughout the design process, and
-   [Involving users in evaluating web
    accessibility](https://www.w3.org/WAI/eval/users.html).

**Accessibility standards** also have an important role in accessible
design. For example, understanding the basic [Accessibility
Principles]({{ site.github.url }}/fundamentals/accessibility-principles/) and
using them for developing and evaluating early prototypes helps the
development team provide basic accessibility in the earliest stages.
Addressing accessibility at later stages becomes increasingly difficult.

Also, usability processes and user involvement alone cannot address all
accessibility issues. Even large projects cannot cover the diversity of
disabilities, adaptive strategies, and assistive technologies.
Accessibility guidelines, standards, and techniques ensure that the wide
range of issues are adequately covered.

Conclusion
----------

Accessibility practitioners and researchers can incorporate usability
techniques to improve 'usable accessibility'. User experience designers
and researchers can incorporate accessibility to make their designs work
better for more people in more situations. Addressing accessibility,
usability, and inclusion together can more effectively lead to a more
accessible, usable, and inclusive web for everyone. Resources to help
are linked throughout this page.

For more on this topic, see [The role of accessibility in a universal
web](http://dspace.mit.edu/handle/1721.1/88013), which:

-   provides a more in-depth exploration of the importance and benefits
    of accessibility as a distinct discipline, and
-   encourages increased communication and coordination between
    accessibility, usability, and inclusion research and practice.

