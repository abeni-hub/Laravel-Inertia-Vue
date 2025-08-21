<template>
  <div>
    <header class="bg-gray-800 text-white p-4">
        <nav class="flex justify-between items-center justify between p-4 
        max-w-screen-lg mx-auto">

           <div class="space-x-6">
            <a href="/">Home</a>
            <a href="/about">About</a>
           </div>
        </nav>
    </header>
    <main class="p-4">
        <slot></slot>
    </main>
  </div>
</template>