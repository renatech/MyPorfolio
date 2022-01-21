<template>
  <section id="contact" class="px-4 py-20 hide-slideUp">
    <div class="max-w-5xl mx-auto">
      <div
        class="
          flex
          md:flex-row
          flex-col
          items-center
          px-8
          py-8
          rounded-3xl
          bg-primary-700
          justify-between
          diagonal-bg
        "
      >
        <div class="w-full md:w-5/12">
          <div class="text-left mb-5 font-bold">
            <span class="font-mono block text-primary-300 text-lg"
              >04 Say Hello</span
            >
            <h2 class="text-white text-2xl md:text-5xl mb-3">Get in Touch</h2>
          </div>
          <p class="text-primary-200 text-sm">
            I am very open to collaborations and consultations. You could reach
            me on my social media handles or email.
            
          </p>
        </div>
        <div class="md:w-36 w-full my-5">
          <action-e-link
            :extra-css="['btn-secondary-inverse', 'btn-rounded']"
            href="mailto:samuelserenaluv@gmail.com&subject=Hello Serena"
            target="_blank"
            >Say Hello</action-e-link
          >
        </div>
      </div>
    </div>
    <div
      class="max-w-5xl text-gray-500 text-sm font-mono mx-auto text-center mt-7"
    >
      Designed by
      <a
        href="http://sundev.netlify.app"
        class="text-primary-600 font-sans hover:text-primary-800"
        >Serena Hubert </a
      >
    </div>
  </section>
</template>

<script>
export default {}
</script>

<style scoped>
.diagonal-bg {
  background-color: #442db6;
  background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='112' height='92' viewBox='0 0 112 92'%3E%3Cg fill='%23372980' fill-opacity='0.4'%3E%3Cpath fill-rule='evenodd' d='M72 10H40L16 20H0v8h16l24-14h32l24 14h16v-8H96L72 10zm0-8H40L16 4H0v8h16l24-6h32l24 6h16V4H96L72 2zm0 84H40l-24-6H0v8h16l24 2h32l24-2h16v-8H96l-24 6zm0-8H40L16 64H0v8h16l24 10h32l24-10h16v-8H96L72 78zm0-12H40L16 56H0v4h16l24 14h32l24-14h16v-4H96L72 66zm0-16H40l-24-2H0v4h16l24 6h32l24-6h16v-4H96l-24 2zm0-16H40l-24 6H0v4h16l24-2h32l24 2h16v-4H96l-24-6zm0-16H40L16 32H0v4h16l24-10h32l24 10h16v-4H96L72 18z'/%3E%3C/g%3E%3C/svg%3E");
}
</style>
