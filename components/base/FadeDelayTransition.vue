<template>
  <transition
    enter-active-class="transition-opacity duration-[700ms] delay-200 ease-out"
    enter-from-class="opacity-0"
    enter-to-class="opacity-100"
    leave-active-class="transition-opacity duration-[700ms] delay-200 ease-in"
    leave-from-class="opacity-100"
    leave-to-class="opacity-0"
  >
    <slot></slot>
  </transition>
</template>
