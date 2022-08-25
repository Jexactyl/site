<template>
  <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 my-10">
    <div class="lg:text-center">
      <p class="mt-2 text-3xl text-green-300 font-extrabold tracking-tight sm:text-4xl">Full of features and functions to make your users rejoice.</p>
      <p class="mt-4 max-w-3xl text-xl text-gray-500 lg:mx-auto">
        Jexactyl is an open-source, feature-rich panel built on <a href="https://pterodactyl.io">Pterodactyl</a> which offers many
        features which make running your next game server easier.
      </p>
    </div>
    <div class="mt-10">
      <dl class="space-y-10 md:space-y-0 md:grid md:grid-cols-2 md:gap-x-8 md:gap-y-10">

        <div class="relative">
          <dt>
            <div class="absolute flex items-center justify-center h-12 w-12 rounded-md bg-green-300">
              <fa-icon icon="fa-cog" class="w-6 h-6" />
            </div>
            <p class="ml-16 text-lg font-semibold text-white">
              Fully customizable, at the click of a button.
            </p>
          </dt>
          <dd class="mt-2 ml-16 text-gray-500">
              Jexactyl features a clean and simple admin interface for controlling (almost!) every single major feature via the UI.
              Toggle user registration, change the reward for referring users and much much more.
          </dd>
        </div>

        <div class="relative">
          <dt>
            <div class="absolute flex items-center justify-center h-12 w-12 rounded-md bg-green-300">
              <fa-icon icon="fa-cubes" class="w-6 h-6" />
            </div>
            <p class="ml-16 text-lg font-semibold text-white">Designed for Minecraft and much, much more.</p>
          </dt>
          <dd class="mt-2 ml-16 text-gray-500">
            With features such as a Spigot plugin manager and advanced metrics per-instance, you&apos;ll have no trouble with getting
            the next Hypixel up and running.
          </dd>
        </div>

        <div class="relative">
          <dt>
            <div class="absolute flex items-center justify-center h-12 w-12 rounded-md bg-green-300">
              <fa-icon icon="fa-code-commit" class="w-6 h-6" />
            </div>
            <p class="ml-16 text-lg font-semibold text-white">Open and transparent, down to the core.</p>
          </dt>
          <dd class="mt-2 ml-16 text-gray-500">
            The code behind Jexactyl is fully open and available at our <a href="https://github.com/jexactyl">GitHub</a>,
            in order to improve transparency and improve our software based on user feedback.
          </dd>
        </div>

        <div class="relative">
          <dt>
            <div class="absolute flex items-center justify-center h-12 w-12 rounded-md bg-green-300">
              <fa-icon icon="fa-desktop" class="w-6 h-6" />
            </div>
            <p class="ml-16 text-lg font-semibold text-white">Functional, yet also beautiful.</p>
          </dt>
          <dd class="mt-2 ml-16 text-gray-500">
            Jexactyl focuses on improving and adding to the existing UI from Pterodactyl, ensuring
            a quality experience for all users. Components are easily modifiable and consist of dark
            colors with prominent content.
          </dd>
        </div>

      </dl>
    </div>
  </div>
</template>

<script lang="ts">
import { library } from '@fortawesome/fontawesome-svg-core'
import { faCog, faArrowDown, faCubes, faCodeCommit, faDesktop } from '@fortawesome/free-solid-svg-icons'

library.add(faCog, faArrowDown, faCubes, faCodeCommit, faDesktop)

export default {}
</script>
