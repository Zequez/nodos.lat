<script lang="ts">
  import { maximizeFontSize } from '@/center/utils/maximizeFontSize'
  import icon from './icon.png'
</script>

<svelte:head>
  <title>*.nodos.lat</title>
  <link rel="icon" type="image/png" href={icon} />
</svelte:head>

<div
  class="font-mono flex-col min-h-screen w-screen flexcc bg-stone-300 text-stone-800"
>
  <div
    class="flex flex-col w-screen-sm max-w-full px6 text-center relative py12 space-y-6"
  >
    <h1
      use:maximizeFontSize={[0.8, 24]}
      class="text-8 xs:text-12 sm:text-20 whitespace-nowrap"
    >
      *.nodos.lat
    </h1>
    <div class="mb6 text-center italic">
      Cada nodo es<br />un espacio digital<br />autónomo programable<br
      />sostenido por alguien<br />en servicio del<br />principio de<br />la
      Cooperación
    </div>
    <div>
      <div class="uppercase underline underline-(offset-4px)">
        Nodos en esta dirección
      </div>
      <div>
        <a href="https://agroeco.mdp.nodos.lat">agroeco.mdp.nodos.lat</a>
      </div>
      <div>
        <a href="https://mogotes.mdp.nodos.lat">mogotes.mdp.nodos.lat</a>
      </div>
    </div>
    <div class="bg-white/30 rounded-md py6 px6"
      >nodos.lat no es una marca, ni un proyecto, ni tiene ningún significado,
      es solo un dominio web barato de rentar que lo pongo a disposición para
      conectar nodos. El ícono de la página es un coral, cuya forma refleja el
      organigrama de los <a href="https://gameworldtheory.mystrikingly.com/"
        >Mundos de juego Gaianos</a
      >.</div
    >
    <div>
      Administración de *.nodos.lat:
      <a href="https://ezequielschwartzman.org">Ezequiel Schwartzman</a>
    </div>

    <div>
      Estás invitad@ a usar el
      <a href="https://github.com/zequez/web-environment"
        >Campo de Programación de Nodos</a
      >
      que yo sostengo para facilitar tus propios nodos. Y a contactarme si querés
      ayuda.
    </div>

    <div>¿Estás en el equipo?</div>
  </div>
</div>

<style>
  a {
    @apply text-sky-600 underline underline-offset-4 hover:(text-sky-400 underline-2);
  }
</style>
