<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><polygon points="10.97,10 15.5,3 13.71,3 10,8.74 6.29,3 4.5,3 9.03,10 5.5,10 5.5,11.5 9.25,11.5 9.25,17 10.75,17 10.75,11.5 14.5,11.5 14.5,10"/></g></svg>