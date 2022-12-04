<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><polygon points="16.5,13.5 3.5,13.5 3.5,4.5 11,4.5 11,3 2,3 2,15 7,15 7,17 13,17 13,15 18,15 18,11 16.5,11"/><polygon points="14.48,11 18,7.48 16.94,6.42 15.25,8.11 15.25,3 13.75,3 13.75,8.14 12.06,6.45 11,7.52"/></g></g></svg>