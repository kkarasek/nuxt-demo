<template>
  <NuxtLayout>
      <header>
        <ul class="flex gap-1">
          <li>
            <NuxtLink to="/">Home</NuxtLink>
          </li>
          <li>
            <NuxtLink to="/events">Events</NuxtLink>
          </li>
        </ul>
      </header>
      <NuxtPage/>
  </NuxtLayout>
</template>
