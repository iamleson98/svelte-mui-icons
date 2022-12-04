<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/></g><g><g><polygon points="5.06,5 4,6.06 7.94,10 4,13.94 5.06,15 10.06,10"/><polygon points="11,5 9.94,6.06 13.88,10 9.94,13.94 11,15 16,10"/></g></g></svg>