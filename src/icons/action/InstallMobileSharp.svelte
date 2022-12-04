<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><polygon points="14.5,15 5.5,15 5.5,5 12,5 12,1 4,1 4,19 16,19 16,13 14.5,13"/><polygon points="15.23,11 18.75,7.48 17.69,6.42 16,8.11 16,3 14.5,3 14.5,8.14 12.81,6.45 11.75,7.52"/></g></g></svg>