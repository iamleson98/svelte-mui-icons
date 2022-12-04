<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/></g><g><path d="M10,3C6.12,3,2.6,4.53,0,7.01L10,17l10-9.99C17.4,4.53,13.88,3,10,3z M12.56,12.32c-1.53-1.07-3.6-1.07-5.13,0L2.21,7.1 C4.46,5.41,7.17,4.5,10,4.5c2.83,0,5.54,0.91,7.79,2.6L12.56,12.32z"/></g></svg>