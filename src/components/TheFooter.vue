<template>
  <nav fixed bottom-0 w-full text-xl my-6 mx-auto inline-flex justify-center gap-2>
    <button icon-btn @click="toggleDark()">
      <div dark:i-carbon-moon i-carbon-sun />
    </button>

    <a
      icon-btn i-carbon-logo-github
      rel="noreferrer"
      href="https://github.com/Liys15/vitesse-litee"
      target="_blank"
      title="GitHub"
    />
  </nav>
</template>
