<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M17,3H3v14h14V3z M7.5,11v-1h1v2h-3V8h3v1h-2v2H7.5z M10.5,12h-1V8h1V12z M14.5,9h-2v0.5H14v1h-1.5V12h-1V8h3V9z"/></svg>