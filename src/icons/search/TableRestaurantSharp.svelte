<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M18.48,9l-2-5H3.52l-2,5h2.75L3,16h1.5l0.73-4h9.32l0.73,4h1.5L15.5,9H18.48z M5.5,10.5L5.77,9H14l0.27,1.5H5.5z"/></g></svg>