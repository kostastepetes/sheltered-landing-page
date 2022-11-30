<template>
  <div class="pt-24 pb-20 md:pb-16 bg-white p-8 background--alt">
    <div class="container mx-auto text-left opacity-100 text-sm lg:px-4">
      <div
        class="flex flex-col justify-center items-start content-start lg:flex-row mb-4"
      >
        <div class="mb-6 md:mb-0 sm:w-1/2 h-auto">
          <a
            v-scroll-reveal="{ delay: 1000, distance: '5%' }"
            class="cursor-pointer inline-block w-16"
            href="/"
            rel="noopener noreferrer"
          >
            <img
              alt="Sheltered Icon"
              class="w-20 grow rounded-3xl"
              src="@/assets/img/intro/Sheltered Video Call App.png"
            />
          </a>
          <p
            class="mt-32 text-left gt-walsheim-regular text-grey text-sm opacity-50 hidden lg:block"
          >
            © Sheltered 2022-2023
          </p>
        </div>
        <div class="sm:w-1/4 h-auto sm:mt-0 mt-8">
          <div
            class="gt-walsheim-medium text-lg text-grey-darkest mb-4 underline"
          >
            Sheltered
          </div>
          <ul class="list-reset leading-normal cursor-pointer">
            <li class="mb-4 md:mb-2">
              <a
                class="link open-sans-regular text-grey-darker hover-link underline"
                href="https://sheltered.netlify.app/"
                target="_blank"
                rel="noopener noreferrer"
                >Check the Sheltered Video Call</a
              >
            </li>
            <li class="mb-4 md:mb-2">
              <a
                class="link open-sans-regular text-grey-darker hover-link underline"
                href="https://sheltered-chat.netlify.app/"
                target="_blank"
                rel="noopener noreferrer"
                >Check the Sheltered Chat</a
              >
            </li>
            <li class="mb-4 md:mb-2">
              <a
                class="link open-sans-regular text-grey-darker hover-link underline"
                href="#features"
                target="_blank"
                rel="noopener noreferrer"
                >Learn more about Sheltered</a
              >
            </li>
          </ul>
        </div>
        <div></div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer"
};
</script>
