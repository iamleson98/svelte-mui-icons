<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/></g><g><g><polygon points="14.94,15 16,13.94 12.06,10 16,6.06 14.94,5 9.94,10"/><polygon points="9,15 10.06,13.94 6.12,10 10.06,6.06 9,5 4,10"/></g></g></svg>