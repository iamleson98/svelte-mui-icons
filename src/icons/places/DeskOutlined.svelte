<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/></g><g><path d="M2,5v10h1.5V6.5H12V15h1.5v-1.5h3V15H18V5H2z M13.5,6.5h3v2h-3V6.5z M13.5,12v-2h3v2H13.5z"/></g></svg>