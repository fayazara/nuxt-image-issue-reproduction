<template>
  <main class="min-h-screen bg-slate-100 space-y-8 p-12">
    <div>
      <h2 class="text-xl font-bold mb-2">A local png image</h2>
      <nuxt-img src="/eiffel-tower.png" sizes="sm:100vw md:50vw lg:1000px" />
    </div>
    <div>
      <h2 class="text-xl font-bold mb-2">A local jpg image</h2>
      <nuxt-img src="/empire-state.jpg" sizes="sm:100vw md:50vw lg:1000px" />
    </div>
    <div>
      <h2 class="text-xl font-bold mb-2">A remote url</h2>
      <nuxt-img
        src="https://images.unsplash.com/photo-1512453979798-5ea266f8880c?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1770&q=80"
        sizes="sm:100vw md:50vw lg:1000px"
      />
    </div>
  </main>
</template>
