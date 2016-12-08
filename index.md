---
layout: default
title: Accessibility, Usability, and Inclusion
subtitle: Related Aspects of a Web for Everyone
status: editors-draft
---

  <h2 id="introduction" class="no-display">Introduction</h2>
  <p><em>Accessibility, usability, and inclusion</em> are closely related aspects in creating a web that works for everyone. Their goals, approaches, and guidelines overlap significantly. When designing and developing websites and applications, it is most effective to address them together.</p>
  <p>There are a few situations when it's important to focus specifically on one aspect, such as when researching accessibility needs of people with disabilities to help develop standards and policies.</p>
  <p class="listintro">This article briefly:</p>
  <ul class="listafterpul">
    <li>explains the distinctions and overlaps between accessibility, usability, and inclusive design,</li>
    <li>points out the importance of maintaining the focus of accessibility on people with disabilities, and</li>
    <li>encourages increased coordination across accessibility, usability, and inclusion practices.</li>
  </ul>

  <h2 id="terms">Distinctions and Overlaps</h2>
  <dl>
    <dt id="accessibility"><strong>Accessibility</strong></dt>
      <dd><em>Accessibility</em> addresses discriminatory aspects related to equivalent user experience for people with disabilities. For the web, accessibility means that people with disabilities can equally perceive, understand, navigate, and interact with websites and tools, and that they can contribute equally without barriers. For more information, see the <a href="https://www.w3.org/standards/webdesign/accessibility">Accessibility introduction</a>.</dd>
    <dt id="usability"><strong>Usability</strong></dt>
    <dd><em>Usability</em>, including <em>user experience design</em> is about designing products to be effective, efficient, and satisfying. This may include general aspects that impact everyone and do not disproportionally impact people with disabilities. Moreover, the needs of people with disabilities are often not sufficiently addressed in usability practice and research.</dd>
    <dt id="inclusion"><strong>Inclusion</strong></dt>
      <dd><em>Inclusion</em>, also <em>universal design</em> and <em>design for all</em>, is about ensuring involvement of everyone to the greatest extent possible. It addresses a broad range of issues including access to and quality of hardware, software, and Internet connectivity; computer literacy and skills; economic situation; education; geographic location; age; and language &mdash; as well as disability.</dd>
  </dl>

  <h3 id="accessible-usable">Accessibility and Usability</h3>
  <p>While accessibility focuses on people with disabilities, many accessibility requirements also improve usability for everyone. Accessibility especially benefits people in limiting situations, such as using the web on a mobile phone when visual attention is elsewhere, in bright sunlight, in a dark room, and in quiet or noisy environments. Accessibility also addresses functional limitations aquired by age, even though some people may not identify these as &quot;disability&quot;.</p>
  <p>Accessibility includes:</p>
  <ul class="listspaced">
  <li><strong>Requirements that are technical and relate to the underlying code rather than to the visual appearance</strong> &mdash; for example, they ensure that websites work well with assistive technologies such as screen readers that read aloud web pages, screen magnifiers that enlarge web pages, and voice recognition software that is used to input text. These aspects are typically not a focus of usability research and practice.</li>
    <li><strong>Requirements that relate to user interaction and visual design</strong> &mdash; they are included in accessibility requirements because they can be significant barriers to people with disabilities. For example, understandable instructions and feedback for website forms and applications is good usability; and this is also an accessibility requirement because many people with cognitive and learning disabilities are otherwise excluded.</li>
  </ul>
  <p>Thus accessibility and usability overlap significantly. According to <a href="http://www.iso.org/iso/catalogue_detail.htm?csnumber=16883"><acronym title="International Organization for Standardization">ISO</acronym> 9241-11</a>, usability is defined as the &quot;extent to which a product can be used by specified users to achieve specified goals effectively, efficiently and with satisfaction in a specified context of use&quot;. This could address accessibility <em><strong>when</strong></em> &quot;specified users&quot; includes people with a range of disabilities and &quot;specified context of use&quot; includes accessibility considerations such as assistive technologies. However, the needs of people with disabilities are often not sufficiently addressed in usability practice and research.</p>

  <h3 id="inclusive-design">Accessibility and Inclusion</h3>
  <p class="listintro">Several accessibility requirements also benefit people and situations that are a focus of inclusive design. For example, <a href="https://www.w3.org/WAI/bcase/soc#groups">Web Accessibility Benefits People With and <em>Without</em> Disabilities</a> describes accessibility benefits for:</p>
  <ul class="listafterpul">
    <li>people with low literacy or not fluent in the language</li>
    <li>people with low bandwidth connections or using older technologies</li>
    <li>new and infrequent users</li>
    <li><a href="https://www.w3.org/WAI/mobile/overlap">mobile device users</a></li>
  </ul>
  <p>However, accessibility focuses on disability and does not try to address broader issues. Other efforts, such as <a href="https://www.w3.org/International/">internationalization</a>, address other inclusion issues. Keeping accessibility focused on disabilities encourages research and development on the specific needs of people with disabilities, and solutions that are optimized for these specific needs.</p>

  <h2 id="accessible-design">Accessible Design</h2>
  <p>There are <a href="https://www.w3.org/WAI/guid-tech.html">guidelines, standards, and techniques</a>, such as the Web Content Accessibility Guidelines (<a href="http://www.w3.org/WAI/intro/wcag">WCAG</a>), which is the international standard <a href="https://www.w3.org/blog/2012/10/wcag-20-is-now-also-isoiec-405/">ISO/IEC 40500</a>. Yet when designers, developers, and project managers approach accessibility as a checklist to meet standards, the focus is only on the technical aspects of accessibility, and the human interaction aspect is often lost, and accessibility is not achieved.</p>
  <p>Combining accessibility standards and usability processes with real people ensures that web design is technically and functionally usable by people with disabilities. This is referred to as <em>usable accessibility</em> or <em>accessible user experience (UX)</em>.</p>

  <h3 id="usable-accessibility">Usable Accessibility</h3>
  <p>Web designers and developers can use usability processes, methods, and techniques, to address the user interface component of accessibility. While the considerations of people with disabilities are not always included in common practices, they can be easily integrated into user experience design.</p>
  <p class="listintro">A key aspect is incorporating <strong>real people</strong> in design:</p>
  <ul class="listafterpul">
    <li>Ensuring that everyone involved in web projects understands the basics of <a href="https://www.w3.org/WAI/intro/people-use-web">how people with disabilities use the Web</a>,</li>
    <li><a href="https://www.w3.org/WAI/users/involving">Involving users with disabilities</a> early and throughout the design process, and </li>
    <li><a href="https://www.w3.org/WAI/eval/users.html">Involving users in evaluating web accessibility</a>.</li>
  </ul>
  <p id="technical-standards"><strong>Accessibility standards</strong> also have an important role in accessible design. For example, understanding the basic <a href="https://www.w3.org/WAI/intro/people-use-web/principles">Accessibility Principles</a> and using them for developing and evaluating early prototypes helps the development team provide basic accessibility in the earliest stages. Addressing accessibility at later stages becomes increasingly difficult.</p>
  <p>Also, usability processes and user involvement alone cannot address all accessibility issues. Even large projects cannot cover the diversity of disabilities, adaptive strategies, and assistive technologies. Accessibility guidelines, standards, and techniques ensure that the wide range of issues are adequately covered.</p>

  <h2 id="conclusion">Conclusion</h2>
  <p>Accessibility practitioners and researchers can incorporate usability techniques to improve 'usable accessibility'. User experience designers and researchers can incorporate accessibility to make their designs work better for more people in more situations. Addressing accessibility, usability, and inclusion together can more effectively lead to a more accessible, usable, and inclusive web for everyone. Resources to help are linked throughout this page.</p>
  <p class="listintro">For more on this topic, see <a href="http://dspace.mit.edu/handle/1721.1/88013">The role of accessibility in a universal web</a>, which:</p>
  <ul class="listafterpul">
    <li>provides a more in-depth exploration of the importance and benefits of accessibility as a distinct discipline, and</li>
    <li>encourages increased communication and coordination between accessibility, usability, and inclusion research and practice.</li>
  </ul>
