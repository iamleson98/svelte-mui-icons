<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><polygon points="8,16 6.5,16 6.5,7.5 14.13,7.5 12.94,6.31 14,5.25 17,8.25 14,11.25 12.94,10.19 14.13,9 8,9"/></g></svg>