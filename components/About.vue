<template>
  <section id="about" class="px-4 py-20">
    <div class="max-w-5xl mx-auto">
      <div class="mb-5 flex items-center max-w-md">
        <h2 class="text-gray-900 text-3xl font-bold hide-slideInRight">
          <span class="font-mono text-primary-600 text-lg mr-2">03</span> About
          Me
        </h2>
        <div class="ml-4 flex-grow border-b-2"></div>
      </div>
      <div
        class="
          flex flex-col-reverse
          lg:flex-row lg:justify-between
          hide-slideInLeft
        "
      >
        <div class="text-gray-600 text-base lg:w-6/12">
          <p class="mb-5">
            My name is Serena, Lorem ipsum dolor sit amet consectetur
            adipisicing elit. Assumenda id eius deleniti qui odio architecto
            voluptate placeat voluptas iusto accusamus, ex repudiandae omnis
            consequuntur sequi perferendis pariatur suscipit, quidem inventore.
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Quidem illo
            quod pariatur eos ducimus voluptatibus architecto doloremque?
            Sapiente unde magnam fugiat cupiditate amet nisi, ratione quisquam
            nihil illo? Similique, vel!
          </p>
          <p class="mb-5">
             My interest in web development started back in 2014 When I went on holiday then I registered for 
             Java programming language just to pass cos 201(intoduction to Java) a 200 Level course in first semester that
             was when my fear for coding disappeard.
          </p> 
          <p class="mb-5">
            Here are a few of the web tools I currently use and enjoy
          </p>
          <ul class="tool-list">
            <li>Javascript</li>
            <li>PHP 8</li>
            <li>CSS 3</li>
            <li>TailwindCSS</li>
            <li>Vue Js</li>
            <li>Laravel Framework</li>
            <li>Figma</li>
            <li>NodeJs</li>
            <li>Heroku</li>
            <li>Git</li>
          </ul>
        </div>
        <div class="mx-auto lg:ml-auto mb-5 lg:mb-0 w-60 hide-slideUp">
          <img
            src="/profile_image.png"
            class="w-full bg-black rounded-3xl"
            alt="Serena's profile image"
          />
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {}
</script>

<style>
.tool-list {
  @apply grid gap-2 grid-cols-2;
}
.tool-list li {
  @apply mb-5 text-gray-800 relative capitalize pl-5;
}
.tool-list li::before {
  content: '▹';
  @apply text-primary-400 top-0 left-0 absolute text-base;
}
</style>
