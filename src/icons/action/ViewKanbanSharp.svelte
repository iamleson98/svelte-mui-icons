<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M17,3H3v14h14V3z M7.5,14H6V6h1.5V14z M10.75,10h-1.5V6h1.5V10z M14,12h-1.5V6H14V12z"/></g></g></svg>