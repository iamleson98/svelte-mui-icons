<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/></g><g><path d="M11.25,3H6v7H4.5v1.5H6V13H4.5v1.5H6V17h1.5v-2.5H11V13H7.5v-1.5h3.75c2.35,0,4.25-1.9,4.25-4.25C15.5,4.9,13.6,3,11.25,3z M11.25,10H7.5V4.5h3.75C12.77,4.5,14,5.73,14,7.25S12.77,10,11.25,10z"/></g></svg>