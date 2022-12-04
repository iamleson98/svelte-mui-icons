<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M16.5,9v6H18V9H16.5z M2,18h13v-1.5H5.62L16.5,5.62V7.5H18V2L2,18z M18,18h-1.5v-1.5H18V18z"/></svg>