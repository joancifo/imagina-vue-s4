<template>
  <h1>Estàs veient la categoria {{ $route.params.categoria }}</h1>

  <ul>
    <li>/ -> index.vue</li>
    <li>/categoria -> categoria/index.vue</li>
    <li>/categoria/:categoria -> categoria/[categoria]/index.vue</li>
    <li>
      /categoria/:categoria/producte -> categoria/[categoria]/producte/index.vue
    </li>
    <li>
      /categoria/:categoria/producte/:producte ->
      categoria/[categoria]/producte/[producte].vue
    </li>
  </ul>
</template>
