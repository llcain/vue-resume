<template lang="pug">
main.max-w-3xl.mx-auto.p-6.font-sans.text-gray-800
  // Header
  section.text-center.mb-8
    h1.text-4xl.font-bold.mb-1 LaQuisha Cain
    ul.text-lg.space-y-1
      li 📞 573-303-7028
      li ✉️ llcain2012@gmail.com
      li 🔗 
        a(href="https://www.linkedin.com/in/YOUR_LINKEDIN", target="_blank", rel="noopener") LinkedIn
      li 🌐 
        a(href="https://heroic-torte-417c1a.netlify.app", target="_blank", rel="noopener") Portfolio Website

  // Experience
  section.mb-10
    h2.text-2xl.font-semibold.mb-4.border-b.pb-1 Experience
    .mb-6
      h3.text-xl.font-medium Full-Stack Developer – Web Developer
      p.text-sm.text-gray-600 May, 2024 – Present
      ul.list-disc.list-inside.mt-2.space-y-1
        li Built and maintained responsive web applications using Vue.js and Tailwind CSS.
        li Collaborated with UX designers to implement clean, accessible UI components.
        li Integrated REST APIs using Axios and improved load performance by 25%.
    . 
      h3.text-xl.font-medium Web Developer – Web Developer
      p.text-sm.text-gray-600 March, 2020 - Present
      ul.list-disc.list-inside.mt-2.space-y-1
        li Worked with senior developers to build marketing sites using Nuxt.js.
        li Wrote reusable Pug templates and contributed to style consistency with Tailwind.

  // Skills
  section.mb-10
    h2.text-2xl.font-semibold.mb-4.border-b.pb-1 Skills
    ul.grid.grid-cols-2.gap-y-1.list-disc.list-inside
      li Vue 3 / Nuxt
      li Tailwind CSS
      li Pug
      li Vuestic UI
      li JavaScript / TypeScript
      li REST APIs / Axios
      li Amplify UI
      li SST / AWS (StaticSite, Lambda)
      li Git / GitHub
      li netlify

  // Projects
  section
    h2.text-2xl.font-semibold.mb-4.border-b.pb-1 Projects
    .mb-4
      h3.text-xl.font-medium Vue Customer Inventory Website
      p.text-sm.text-gray-600 [Vite + Pug + Tailwind + SST]
      p.mt-1
        | Personal resume site deployed on AWS using SST's StaticSite and ApiGateway. Features a responsive design and ATS-friendly layout.
        br
        | 🔗 
        a(href="https://your-live-site.com", target="_blank") Live Site
        |  | 📁 
        a(href="https://github.com/your-username/vue-resume", target="_blank") GitHub
      h3.text-xl.font-medium Project Name
      p.text-sm.text-gray-600 Short description of what this project does or solves.
      p.mt-1
        | 🔗 
        a(href="https://project-link.com", target="_blank") Live Site
        |  | 📁 
        a(href="https://github.com/your-username/project-repo", target="_blank") GitHub
</template>
