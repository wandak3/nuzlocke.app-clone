<script>
  import { Icon } from '$c/core'
  import { Coffee, GitHub, Discord, Heart } from '$icons'
</script>

<footer class={$$restProps.class || ''}>

  <span class='inline-flex items-center mb-2'>Made by <strong class="mx-1"><a href="https://github.com/domtronn">Domtronn</a></strong></span>
  <br />
  <span class='inline-flex items-center mb-2'>Continue to added content by <strong class="mx-1">Wumps</strong></span>
  <br />
  All content & design © Pokémon Nuzlocke Tracker, 2021-{(new Date()).getFullYear()}. <a href='/privacy-policy'>Privacy Policy</a>. <a href='/credit'>Credits</a>.
  <br class='hidden md:block' />
  Pokémon images & names © 1995-2021 Nintendo/Creatures Inc./GAME FREAK inc. TM
</footer>

<!-- svelte-ignore css-unused-selector -->
<style>
  footer { @apply text-center w-full absolute bottom-4 md:bottom-2 sm:my-6 px-4 text-tiny md:text-xs text-gray-500 dark:text-gray-400 leading-3 z-20 h-max; }
  footer > p { @apply flex justify-center text-2xl gap-x-2; }
  footer a,
  footer button { @apply transition-colors; }
  footer button:hover, footer a:hover, { @apply text-black }
  :global(.dark) footer button:hover, :global(.dark) footer a:hover { @apply text-white }
  footer button { @apply p-3 }
</style>
