<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><polygon points="14.5,5.87 14.5,12 7,12 7,17 5.5,17 5.5,10.5 13,10.5 13,5.87 11.81,7.06 10.75,6 13.75,3 16.75,6 15.69,7.06"/></g></svg>