<template>
  <!-- NAVBAR -->
  <div class="navbar bg-base-100">
    <div class="flex-1">
      <a class="btn btn-ghost normal-case text-xl">daisyUI</a>
    </div>
    <div class="flex-none">
      <ul class="menu menu-horizontal p-0">
        <li><a>Home</a></li>
        <li><a>About</a></li>
        <li><a>Blog</a></li>
        <li><a>Contact Us</a></li>
        <li>
          <a><button class="btn">Download App</button></a>
        </li>
      </ul>
    </div>
  </div>

  <!-- HERO SECTION -->
  <div class="hero min-h-screen bg-base-200">
    <div class="hero-content flex-col lg:flex-row">
      <img
        src="https://placeimg.com/260/400/arch"
        class="max-w-sm rounded-lg shadow-2xl"
      />
      <div>
        <h1 class="text-5xl font-bold">Box Office News!</h1>
        <p class="py-6">
          Provident cupiditate voluptatem et in. Quaerat fugiat ut assumenda
          excepturi exercitationem quasi. In deleniti eaque aut repudiandae et a
          id nisi.
        </p>
        <button class="btn btn-primary">Get Started</button>
      </div>
    </div>
  </div>

  <div class="stats shadow">
    <div class="stat">
      <div class="stat-figure text-primary">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 24 24"
          class="inline-block w-8 h-8 stroke-current"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z"
          ></path>
        </svg>
      </div>
      <div class="stat-title">Total Likes</div>
      <div class="stat-value text-primary">25.6K</div>
      <div class="stat-desc">21% more than last month</div>
    </div>

    <div class="stat">
      <div class="stat-figure text-secondary">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 24 24"
          class="inline-block w-8 h-8 stroke-current"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M13 10V3L4 14h7v7l9-11h-7z"
          ></path>
        </svg>
      </div>
      <div class="stat-title">Page Views</div>
      <div class="stat-value text-secondary">2.6M</div>
      <div class="stat-desc">21% more than last month</div>
    </div>

    <div class="stat">
      <div class="stat-figure text-secondary">
        <div class="avatar online">
          <div class="w-16 rounded-full">
            <img src="https://placeimg.com/128/128/people" />
          </div>
        </div>
      </div>
      <div class="stat-value">86%</div>
      <div class="stat-title">Tasks done</div>
      <div class="stat-desc text-secondary">31 tasks remaining</div>
    </div>
  </div>

  <button class="btn">Hello daisyui</button>

  <!-- FOOTER -->
  <footer class="footer p-10 bg-base-200 text-base-content">
    <div>
      <span class="footer-title">Services</span>
      <a class="link link-hover">Branding</a>
      <a class="link link-hover">Design</a>
      <a class="link link-hover">Marketing</a>
      <a class="link link-hover">Advertisement</a>
    </div>
    <div>
      <span class="footer-title">Company</span>
      <a class="link link-hover">About us</a>
      <a class="link link-hover">Contact</a>
      <a class="link link-hover">Jobs</a>
      <a class="link link-hover">Press kit</a>
    </div>
    <div>
      <span class="footer-title">Legal</span>
      <a class="link link-hover">Terms of use</a>
      <a class="link link-hover">Privacy policy</a>
      <a class="link link-hover">Cookie policy</a>
    </div>
  </footer>
  <footer
    class="
      footer
      px-10
      py-4
      border-t
      bg-base-200
      text-base-content
      border-base-300
    "
  >
    <div class="items-center grid-flow-col">
      <svg
        width="24"
        height="24"
        viewBox="0 0 24 24"
        xmlns="http://www.w3.org/2000/svg"
        fill-rule="evenodd"
        clip-rule="evenodd"
        class="fill-current"
      >
        <circle cx="12" cy="12" r="12" />
      </svg>
      <p>ACME Industries Ltd. <br />Providing reliable tech since 1992</p>
    </div>
    <div class="md:place-self-center md:justify-self-end">
      <div class="grid grid-flow-col gap-4">
        <a
          ><svg
            xmlns="http://www.w3.org/2000/svg"
            width="24"
            height="24"
            viewBox="0 0 24 24"
            class="fill-current"
          >
            <circle cx="12" cy="12" r="12" /></svg
        ></a>
        <a
          ><svg
            xmlns="http://www.w3.org/2000/svg"
            width="24"
            height="24"
            viewBox="0 0 24 24"
            class="fill-current"
          >
            <circle cx="12" cy="12" r="12" /></svg
        ></a>
        <a
          ><svg
            xmlns="http://www.w3.org/2000/svg"
            width="24"
            height="24"
            viewBox="0 0 24 24"
            class="fill-current"
          >
            <circle cx="12" cy="12" r="12" /></svg
        ></a>
      </div>
    </div>
  </footer>
</template>
