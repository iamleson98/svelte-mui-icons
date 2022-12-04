<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><polygon points="2.5,5 1,5 1,17 15.68,17 15.68,15.5 2.5,15.5"/><polygon points="18,4 11,4 9,2 4,2 4,14 18,14"/></g></g></svg>