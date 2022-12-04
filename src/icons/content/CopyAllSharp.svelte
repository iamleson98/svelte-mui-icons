<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M17,2H6v13h11V2z M15.5,13.5h-8v-10h8V13.5z M3,12v-1.5h1.5V12H3z M3,15v-1.5h1.5V15H3z M9,16.5h1.5V18H9V16.5z M3,7.5h1.5 V9H3V7.5z M7.5,18H6v-1.5h1.5V18z M4.5,18H3v-1.5h1.5V18z M4.5,6H3V4.5h1.5V6z M13.49,16.5V18h-1.5v-1.5H13.49z"/></svg>