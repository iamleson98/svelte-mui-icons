<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/></g><g><path d="M16,15.5V3H4v12.5H2V17h16v-1.5H16z M10.75,4.5h1.12v11h-1.12V4.5z M9.25,15.5H8.12v-11h1.12V15.5z M5.5,4.5h1.12v11H5.5 V4.5z M13.38,15.5v-11h1.12v11H13.38z"/></g></svg>