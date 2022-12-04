<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/></g><g><path d="M12.5,13.5v0.99l-5-2.71V9.24L9.83,6.5H13V2H8.5v3.75L6.16,8.5H3V13h3.6l5.9,3.2V18H17v-4.5H12.5z M10,3.5h1.5V5H10V3.5z M6,11.5H4.5V10H6V11.5z M15.5,16.5H14V15h1.5V16.5z"/></g></svg>