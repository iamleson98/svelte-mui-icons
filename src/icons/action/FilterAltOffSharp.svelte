<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><polygon points="2.93,2.93 1.87,3.99 9,11.12 9,16 11,16 11,13.12 16.01,18.13 17.07,17.07"/><polygon points="16.56,4 6.12,4 11.86,9.73"/></g></g></svg>