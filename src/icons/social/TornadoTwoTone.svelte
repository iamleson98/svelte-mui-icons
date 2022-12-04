<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><polygon opacity=".3" points="10,15.08 11.55,12.5 8.45,12.5"/><polygon opacity=".3" points="7.55,11 12.45,11 13.95,8.5 6.05,8.5"/><polygon opacity=".3" points="3.65,4.5 5.15,7 14.85,7 16.35,4.5"/><path d="M1,3l9,15l9-15H1z M10,15.08L8.45,12.5h3.1L10,15.08z M12.45,11h-4.9l-1.5-2.5h7.9L12.45,11z M5.15,7l-1.5-2.5h12.7 L14.85,7H5.15z"/></g></g></svg>