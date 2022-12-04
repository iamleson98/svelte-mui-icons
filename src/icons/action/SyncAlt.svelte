<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><polygon points="18,7 15,4 15,6.25 3,6.25 3,7.75 15,7.75 15,10"/><polygon points="5,10 2,13 5,16 5,13.75 17,13.75 17,12.25 5,12.25"/></g></g></svg>