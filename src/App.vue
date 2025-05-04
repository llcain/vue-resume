<template>
  <main class="max-w-3xl mx-auto p-6 font-sans text-gray-800">
    <!-- Header -->
    <section class="text-center mb-8">
      <h1 class="text-4xl font-bold mb-1">LaQuisha Cain</h1>
      <ul class="text-lg space-y-1">
        <li>📞 <a href="tel:5733037028" class="text-blue-600 hover:underline">573-303-7028</a></li>
        <li>✉️ <a href="mailto:llcain2012@gmail.com" class="text-blue-600 hover:underline">llcain2012@gmail.com</a></li>
        <li>🔗 <a href="https://www.linkedin.com/in/YOUR_LINKEDIN" target="_blank" rel="noopener" class="text-blue-600 hover:underline">LinkedIn</a></li>
        <li>🌐 <a href="https://heroic-torte-417c1a.netlify.app" target="_blank" rel="noopener" class="text-blue-600 hover:underline">Portfolio Website</a></li>
      </ul>
    </section>

    <!-- Experience -->
    <section class="mb-10">
      <h2 class="text-2xl font-semibold mb-4 border-b pb-1">Experience</h2>
      <div class="mb-6">
        <h3 class="text-xl font-medium">Front-End Developer – ABC Corp</h3>
        <p class="text-sm text-gray-600">Jan 2022 – Present</p>
        <ul class="list-disc list-inside mt-2 space-y-1">
          <li>Built and maintained responsive web applications using Vue.js and Tailwind CSS.</li>
          <li>Collaborated with UX designers to implement clean, accessible UI components.</li>
          <li>Integrated REST APIs using Axios and improved load performance by 25%.</li>
        </ul>
      </div>

      <div>
        <h3 class="text-xl font-medium">Web Developer Intern – XYZ Agency</h3>
        <p class="text-sm text-gray-600">Summer 2021</p>
        <ul class="list-disc list-inside mt-2 space-y-1">
          <li>Worked with senior developers to build marketing sites using Nuxt.js.</li>
          <li>Wrote reusable Pug templates and contributed to style consistency with Tailwind.</li>
        </ul>
      </div>
    </section>

    <!-- Skills -->
    <section class="mb-10">
      <h2 class="text-2xl font-semibold mb-4 border-b pb-1">Skills</h2>
      <ul class="grid grid-cols-2 gap-y-1 list-disc list-inside">
        <li>Vue 3 / Nuxt</li>
        <li>Tailwind CSS</li>
        <li>Pug</li>
        <li>Vuestic UI</li>
        <li>JavaScript / TypeScript</li>
        <li>REST APIs / Axios</li>
        <li>SST / AWS (StaticSite, Lambda)</li>
        <li>Git / GitHub</li>
      </ul>
    </section>

    <!-- Projects -->
    <section>
      <h2 class="text-2xl font-semibold mb-4 border-b pb-1">Projects</h2>
      <div class="mb-4">
        <h3 class="text-xl font-medium">Vue Resume Website</h3>
        <p class="text-sm text-gray-600">[Vite + Pug + Tailwind + SST]</p>
        <p class="mt-1">
          Personal resume site deployed on AWS using SST's StaticSite and ApiGateway. Features a responsive design and ATS-friendly layout.
          <br />
          🔗 <a href="https://your-live-site.com" target="_blank" class="text-blue-600 hover:underline">Live Site</a>
          |
          📁 <a href="https://github.com/your-username/vue-resume" target="_blank" class="text-blue-600 hover:underline">GitHub</a>
        </p>
      </div>

      <div>
        <h3 class="text-xl font-medium">Project Name</h3>
        <p class="text-sm text-gray-600">Short description of what this project does or solves.</p>
        <p class="mt-1">
          🔗 <a href="https://project-link.com" target="_blank" class="text-blue-600 hover:underline">Live Site</a>
          |
          📁 <a href="https://github.com/your-username/project-repo" target="_blank" class="text-blue-600 hover:underline">GitHub</a>
        </p>
      </div>
    </section>
  </main>
</template>

<script setup>
// You can define props or data here if needed later.
</script>

<style scoped>
main {
  font-family: 'Inter', sans-serif;
}
</style>
