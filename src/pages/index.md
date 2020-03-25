---
title: Home
sections:
  - type: heroblock
    title: 'Hi, I''m Mio Spruit '
    section_id: hero
    component: HeroBlock
    content: >-
      This section can contain a subtitle or tagline. The recommended length is
      one to three sentences, but can be changed as you prefer.
  - view_all_text: View All
    num_projects_displayed: 6
    section_id: latest-projects
    view_all_url: portfolio/index.html
    subtitle: An optional subtitle of the section
    title: Recent Work
    type: portfolioblock
    layout_style: mosaic
    component: PortfolioBlock
  - type: servicesblock
    title: What I do
    section_id: services
    component: ServicesBlock
    subtitle: Or more what I love to do
    serviceslist:
      - title: Web development
        content: >-
          Web development is a part of what I love to do. Creating websites,
          blogs, web applications. And I got experience in Laravel, Node.js,
          React.js, Vue.js, Git, Bootstrap, SASS, PHP, HTML, JavaScript.
      - title: Interaction design
        content: >-
          Creating interaction designs for mobile, tablet, desktop and other
          devices makes me thrive. I have worked with Creative Cloud, Sketch,
          Adobe XD, Invision and paper prototyping.
      - title: Smart Objects
        content: >-
          This is something I like to do, building smart objects. Working with
          arduino, circuit playground and sensors. Still trying to get better
          with tensorflow and google assistant.
  - type: postsblock
    title: Latest from the Blog
    section_id: latest-posts
    component: PostsBlock
    subtitle: These are my latest posts about me.
    num_posts_displayed: 2
    actions:
      - label: View Blog
        url: blog/index.html
  - type: contactblock
    title: Contact Me
    section_id: contact
    component: ContactBlock
    subtitle: Get in contact with this thing or.... some other way.
menus:
  main:
    title: Home
    weight: 1
template: home
---
