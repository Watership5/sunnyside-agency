<script setup>
  import logo from "../assets/logo.svg"
  import arrow from "../assets/icon-arrow-down.svg"
</script>

<template>
  <section class="hero">
    <nav>
      <img :src="logo" alt="logo"/>
      <ul>
        <li>
          About
        </li>
        <li>
          Services
        </li>
        <li>
          Projects
        </li>
        <button>
            contact
        </button>
      </ul>
    </nav>
    <div class="main-container">
      <h1>
        WE ARE CR<span>E</span>ATIVES
      </h1>
      <img :src="arrow" alt="" class="img"/>
    </div>
  </section>
</template>