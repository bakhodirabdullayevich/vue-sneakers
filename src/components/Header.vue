<template>
  <header class="flex justify-between border-b border-slate-300 p-4">
    <div class="flex items-center gap-4 cursor-pointer">
      <img src="/logo.png" alt="logo" class="w-10" />
      <div>
        <h2 class="text-2xl fond-bold uppercase">Vue Sneakers</h2>
        <p class="text-slate-400">On-Line Store</p>
      </div>
    </div>

    <ul class="flex items-center gap-10">
      <li class="flex items-center gap-3 cursor-pointer text-gray-400 hover:text-black">
        <img src="/cart.svg" alt="Cart" />
        <b> 120 $</b>
      </li>
      <li class="flex items-center gap-3 cursor-pointer text-gray-400 hover:text-black">
        <img src="/heart.svg" alt="Like" />
        <span> Liked</span>
      </li>
      <li class="flex items-center gap-3 cursor-pointer text-gray-400 hover:text-black">
        <img src="/profile.svg" alt="Profile" />
        <span> Profile</span>
      </li>
    </ul>
  </header>
</template>
