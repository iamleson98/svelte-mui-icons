<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><polygon points="12,16 13.5,16 13.5,7.5 5.87,7.5 7.06,6.31 6,5.25 3,8.25 6,11.25 7.06,10.19 5.87,9 12,9"/></g></svg>