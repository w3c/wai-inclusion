---
layout: default
title: Accessibility, Usability, and Inclusion
subtitle: Related Aspects of a Web for All
status: editors-draft
---

  <h2 id="introduction" class="no-display">Introduction</h2>
  <p><em>Accessibility, usability, and inclusive design</em> are closely related. Their goals, approaches, and guidelines overlap significantly.</p>
  <p>In most situations, such as when designing and developing websites and applications, it is most effective to address them together.</p>
  <p>There are a few situations when it's important to focus specifically on one aspect, such as when addressing discrimination against people with disabilities and when defining specific accessibility standards.</p>
  <p class="listintro">This article briefly:</p>
  <ul class="listafterpul">
    <li>explains the distinctions and overlaps between accessibility, usability, and inclusive design,</li>
    <li>points out the importance of maintaining the focus of accessibility on people with disabilities, and</li>
    <li>encourages increased coordination between accessibility, usability, and inclusion.</li>
  </ul>

  <h2 id="terms">Distinctions and Overlaps</h2>
  <dl>
    <dt id="accessibility"><strong>Accessibility</strong></dt>
      <dd><em>Accessibility</em> addresses discriminatory aspects related to equivalent user experience for people with disabilities. For the web, accessibility means that people with disabilities can perceive, understand, navigate, and interact with websites and tools, and that they can contribute equally without barriers. For more information, see the <a href="https://www.w3.org/standards/webdesign/accessibility">Accessibility introduction</a>.</dd>
    <dt id="usability"><strong>Usability</strong></dt>
      <dd><em>Usability</em> and <em>user experience design </em>is about designing products to be effective, efficient, and satisfying. Specifically, <acronym title="International Organization for Standardization">ISO</acronym> defines usability as the &ldquo;extent to which a product can be used by specified users to achieve specified goals effectively, efficiently and with satisfaction in a specified context of use&quot; (in <a href="http://www.iso.org/iso/catalogue_detail.htm?csnumber=16883">ISO 9241-11</a>).</dd>
    <dt id="inclusion"><strong>Inclusion</strong></dt>
    <dd><em>Inclusion</em> or <em>Inclusive design</em>, <em>universal design</em>, and <em>design for all</em> involves designing products, such as websites, to be usable by everyone to the greatest extent possible. Inclusion addresses a broad range of issues including access to and quality of hardware, software, and Internet connectivity; computer literacy and skills; economic situation; education; geographic location; age; and language &mdash; as well as disability.</dd>
  </dl>

  <h3 id="accessible-usable">Accessibility and Usability</h3>
  <p>While accessibility focuses on people with disabilities, many accessibility requirements also improve usability for everyone. Accessibility especially benefits people without disabilities who are in limiting situations, such as using the web on a mobile phone when visual attention is elsewhere, in bright sunlight, in a dark room, in a quiet environment, in a noisy environment, and in an emergency.</p>
  <p>Accessibility includes both:</p>
  <ul class="listspaced">
  <li><strong>Requirements that are more specific to people with disabilities</strong> &mdash; for example, they ensure that websites work well with assistive technologies such as screen readers that read aloud web pages, screen magnifiers that enlarge web pages, and voice recognition software that is used to input text. Most of these requirements are technical and relate to the underlying code rather than to the visual appearance.</li>
    <li><strong>Requirements that are also general usability principles</strong> &mdash; which are included in accessibility requirements because they can be significant barriers to people with disabilities. For example, a website that is developed so that it can be used without a mouse is good usability; and use without a mouse is an accessibility requirement because people with some physical and visual disabilities cannot use a mouse at all. In defining accessibility requirements, care is usually taken to not include aspects that impact all people similarly, and only include aspects that put person with a disability is at a disadvantage relative to a person without a disability.</li>
  </ul>
  <p>Usability and user experience design significantly overlap with accessibility <em><strong>when</strong></em> &quot;specified users&quot; includes people with a range of disabilities and &quot;specified context of use&quot; includes accessibility considerations such as assistive technologies. However, the needs of people with disabilities are often not sufficiently addressed in usability practice and research.</p>
  <p>Additionally, accessibility includes a technical aspect that is usually not a focus of usability. In practice, basic accessibility is a prerequisite for usability.</p>

  <h3 id="inclusive-design">Accessibility and Inclusive Design</h3>
  <p class="listintro">Several accessibility requirements also benefit people and situations that are a focus of inclusive design. For example, <a href="https://www.w3.org/WAI/bcase/soc#groups">Web Accessibility Benefits People With and <em>Without</em> Disabilities</a> describes accessibility benefits to:</p>
  <ul class="listafterpul">
    <li>people with low literacy or not fluent in the language</li>
    <li>people with low bandwidth connections or using older technologies</li>
    <li>new and infrequent users</li>
    <li><a href="https://www.w3.org/WAI/mobile/overlap">mobile device users</a></li>
  </ul>
  <p>However, accessibility focuses on disability and does not try to address broader issues. Other efforts, such as <a href="https://www.w3.org/International/">internationalization</a>, address other inclusion issues.</p>
  <p>While people with disabilities are generally included in the scope of inclusive design, it is important to also maintain  a <strong>specific focus on people with disabilities through accessibility</strong> so that the needs of people with disabilities are not diluted or overshadowed in the broader scope of inclusion. Keeping accessibility focused on disabilities encourages research and development  on the specific needs of people with disabilities, and solutions that are optimized for these specific needs.</p>

  <h2 id="accessible-design">Accessible Design</h2>
  <p>The goal of web accessibility is to make the web work well for <strong>people</strong> with disabilities. Accessible design has both a technical component and a user interface component.</p>
  <p>There are <a href="https://www.w3.org/WAI/guid-tech.html">guidelines, standards, and techniques</a>, such as the Web Content Accessibility Guidelines (<a href="http://www.w3.org/WAI/intro/wcag">WCAG</a>), which is the international standard <a href="https://www.w3.org/blog/2012/10/wcag-20-is-now-also-isoiec-405/">ISO/IEC 40500</a>. If designers, developers, and project managers approach accessibility as a checklist of meeting accessibility standards, the focus is only on the technical aspects of accessibility, and the human interaction aspect is often lost.</p>
  <p>Combining accessibility standards and usability processes with real people ensures that web design is technically and functionally usable by people with disabilities. This is referred to as <em>usable accessibility</em> or <em>accessible user experience (UX)</em>.</p>

  <h3 id="usable-accessibility">Usable Accessibility</h3>
  <p>Web designers and developers can use usability processes, methods, and techniques, such as user-centered design (UCD) process and user experience design, to address the user interface component of accessibility. While the considerations of people with disabilities are not always included in common practices, they can be easily integrated into existing usability processes, methods, and techniques.</p>
  <p class="listintro">A key aspect is incorporating <strong>real people</strong> in design, including:</p>
  <ul class="listafterpul">
    <li>Ensuring that everyone involved in web projects understands the basics of <a href="https://www.w3.org/WAI/intro/people-use-web">how people with disabilities use the Web</a>,</li>
    <li><a href="https://www.w3.org/WAI/users/involving">Involving users with disabilities</a> early and throughout the design process, and </li>
    <li><a href="https://www.w3.org/WAI/eval/users.html">Involving users in evaluating web accessibility</a>.</li>
  </ul>
  <p id="technical-standards"><strong>Accessibility standards</strong> also have an important role in accessible design. For example, understanding the basic <a href="https://www.w3.org/WAI/intro/people-use-web/principles">Accessibility Principles</a> and using the guidelines for developing early prototypes helps the development team provide basic accessibility so that when users do evaluations, they are able to use the prototype enough to provide useful feedback.</p>
  <p>Usability processes and user involvement alone cannot address all accessibility issues. Even large projects cannot cover the diversity of disabilities, adaptive strategies, and assistive technologies. Accessibility guidelines, standards, and techniques ensure that the wide range of issues are adequately covered.</p>

  <h2 id="conclusion">Conclusion</h2>
  <p>Accessibility practitioners and researchers can incorporate usability techniques to improve 'usable accessibility'. User experience designers and researchers can incorporate accessibility to make their designs work better for more people in more situations. Addressing accessibility, usability, and inclusion together can more effectively lead to a more accessible, usable, and inclusive web for everyone. Resources to help are linked throughout this page.</p>
  <p class="listintro"><a href="http://dspace.mit.edu/handle/1721.1/88013">The role of accessibility in a universal web</a> is a related resource that:</p>
  <ul class="listafterpul">
    <li>provides a more in-depth exploration of the importance and benefits of accessibility as a distinct discipline continuing to focus on people with disabilities,</li>
    <li>encourages increased communication and coordination between accessibility, usability, and inclusion research and practice in the design and development of guidelines, websites, browsers, assistive technologies, and other web tools.</li>
  </ul>
