<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/></g><g><path d="M1,3l9,15l9-15H1z M16.35,4.5L14.85,7h-9.7l-1.5-2.5H16.35z M6.05,8.5h7.9l-1.5,2.5h-4.9L6.05,8.5z M8.45,12.5h3.1 L10,15.08L8.45,12.5z"/></g></svg>