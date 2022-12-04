<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><polygon points="9.21,15 12.43,15 16,10 12.43,5 9.21,5 12.79,10"/><polygon points="4.21,15 7.43,15 11,10 7.43,5 4.21,5 7.79,10"/></g></svg>