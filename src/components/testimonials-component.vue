<script setup>
  import jennie from "../assets/image-jennie.jpg"
  import emily from "../assets/image-emily.jpg"
  import thomas from "../assets/image-thomas.jpg"

</script>

<template>
  <article class="testimonials">
    <h1>
      client testimonials
    </h1>
    <section>
      <div>
        <img :src="emily" alt="pfp-emily"/>
        <p>
          We put our trust in Sunnyside and they delivered, making sure our need were met and deadlines were always hit.  
        </p>
        <div>
          <p>
            Emily R.
          </p>
          <p>
            Marketing Director
          </p>
        </div>
      </div>
      <div>
        <img :src="thomas" alt="pfp-thomas"/>
        <p>
          Sunnyside's enthusiasm coupled with their keen interest in our brand's success made it a satisfying and enjoyable experience. 
        </p>
        <div>
          <p>
            Thomas S. 
          </p>
          <p>
            Chief Operating Officer
          </p>
        </div>
      </div>
      <div>
        <img :src="jennie" alt="pfp-jennie"/>
        <p>
          Incredible end result! Our sales increased over 400% when we worked with Sunnyside. Highly recommended! 
        </p>
        <div>
          <p>
            Jennie F.
          </p>
          <p>
            Business Owner
          </p>
        </div>
      </div>
    </section>
  </article>
</template>