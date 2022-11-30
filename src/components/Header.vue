<template>
  <div class="background--alt">
    <nav
      class="container mx-auto flex items-center justify-between flex-wrap pt-6 px-6 md:px-12"
    >
      <div class="flex items-center flex-shrink-0 text-black mr-6">
        <transition appear name="fadeDown">
          <a
            class="cursor-pointer inline-block w-20 grow"
            href="/"
            rel="noopener noreferrer"
          >
            <img
              alt="Sheltered Icon"
              class="w-20 rounded-2xl"
              src="@/assets/img/intro/Sheltered Video Call App.png"
            />
          </a>
        </transition>
      </div>
      <div class="hidden lg:block lg:inline-flex lg:items-center lg:w-auto">
        <div class="text-sm lg:flex-grow">
          <a
            href="#features"
            v-smooth-scroll="{ duration: 1000 }"
            class="block mt-4 lg:inline-block lg:mt-0 cursor-pointer gt-walsheim-regular text-black hover-link mr-5 underline"
          >
            About
          </a>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: "Header"
};
</script>
