<template>
  <div id="app" class="container mx-auto px-4 py-4">
    <div class="flex flex-col">
      <div class="text-center mt-4">
        <ul class="list-reset flex justify-center">
          <li class="mr-6">
            <router-link class="text-purple-light hover:text-purple-dark" to="/">Aigosha</router-link>
          </li>
          <li class="mr-6">
            <router-link class="text-purple-light hover:text-purple-dark" to="/dakosha">Dakosha</router-link>
          </li>
        </ul>
      </div>
      <div class="text-center mt-8">
        <transition enter-active-class="animated rotateIn" leave-active-class="animated rotateOut">
          <router-view/>
        </transition>
      </div>
    </div>
  </div>
</template>
