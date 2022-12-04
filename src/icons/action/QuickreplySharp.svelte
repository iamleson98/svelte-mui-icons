<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><g><polygon points="17,3 3,3 3,17 6,14 13,14 13,9 17,9"/></g><g><polygon points="18,13 16.4,13 17.64,10 14,10 14,14.36 15.45,14.36 15.45,18"/></g></g></g></svg>