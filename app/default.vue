<template>
  <div>
    <header>
      <nav>
        <!-- Your Navbar Component or direct HTML here -->
        <NuxtLink to="/">Home</NuxtLink>
        <NuxtLink to="/about">About</NuxtLink>
        <NuxtLink to="/contact">Contact</NuxtLink>
      </nav>
    </header>
    <main>
      <NuxtPage />
    </main>
    <footer>
      <!-- Your Footer Component or direct HTML here -->
    </footer>
  </div>
</template>