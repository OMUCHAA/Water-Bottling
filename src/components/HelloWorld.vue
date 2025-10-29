<template>
<div class="navbar bg-base-100 shadow-sm fixed z-50">
  <div class="navbar-start">
    <div class="dropdown">
      <div tabindex="0" role="button" class="btn btn-ghost lg:hidden">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor"> <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h8m-8 6h16" /> </svg>
      </div>
      <ul
        tabindex="-1"
        class="menu menu-sm dropdown-content bg-base-100 rounded-box z-1 mt-3 w-52 p-2 shadow">
        <li><a>Explore</a></li>
        <li>
          <a>Home</a>
          <ul class="p-2">
            <li><a>Our Services</a></li>
            <li><a>Solutions</a></li>
          </ul>
        </li>
        <li><a>Contact Us</a></li>
      </ul>
    </div>
    <a class="btn btn-ghost text-xl">Amal Brothers LMT</a>
  </div>
  <div class="navbar-center hidden lg:flex">
    <ul class="menu menu-horizontal px-1">
      <li><a>Home</a></li>
      <li>
        <details>
          <summary>Explore</summary>
          <ul class="p-2">
            <li><a>Services</a></li>
            <li><a>Solutions</a></li>
          </ul>
        </details>
      </li>
      <li><a>Reach Out</a></li>
    </ul>
  </div>
  <div class="navbar-end">
    <a class="btn">Button</a>
  </div>
</div>

<div class="hero bg-base-200 min-h-screen text-center lg:text-left">
  <div class="hero-content flex-col-reverse lg:flex-row-reverse mt-7 sm:mt-10">
    <img
      src="../assets/hero.png"
      class="rounded-lg"
    />
    <div>
      <h1 class="lg:text-6xl md:text-4xl text-3xl font-bold mt-10">Water Bottling Bussiness.</h1>
      <p class="py-6 hidden sm:flex">
        We are committed to delivering clean, refreshing and healthy bottled water that meets the highest standards of purity and taste. Our water goes through advanced filtration and purification processes, ensurikng it is free from impurities while maintaining essential minerals that promote good health.
      </p>
      <button class="btn btn-primary">Get Started</button>
    </div>
  </div>
</div>
</template>
<script setup></script> 