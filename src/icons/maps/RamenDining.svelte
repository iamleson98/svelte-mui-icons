<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M17,3.5V3L5,4.5V5v1v0.5V10H3c0,2.79,1.64,5.19,4,6.32V17h6v-0.68c2.36-1.12,4-3.53,4-6.32H8.5V6.5H17V6H8.5V4.56L17,3.5z M5.5,4.94l1-0.12V6h-1V4.94z M5.5,10V6.5h1V10H5.5z M8,10H7V6.5h1V10z M8,6H7V4.75l1-0.12V6z"/></g></svg>