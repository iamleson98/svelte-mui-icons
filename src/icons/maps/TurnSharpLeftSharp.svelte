<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><polygon points="5.5,5.87 5.5,12 13,12 13,17 14.5,17 14.5,10.5 7,10.5 7,5.87 8.19,7.06 9.25,6 6.25,3 3.25,6 4.31,7.06"/></g></svg>