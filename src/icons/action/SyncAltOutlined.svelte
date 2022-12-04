<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><polygon points="15,4 13.94,5.06 15.13,6.25 3,6.25 3,7.75 15.13,7.75 13.94,8.94 15,10 18,7"/><polygon points="6.06,11.06 5,10 2,13 5,16 6.06,14.94 4.87,13.75 17,13.75 17,12.25 4.87,12.25"/></g></g></svg>