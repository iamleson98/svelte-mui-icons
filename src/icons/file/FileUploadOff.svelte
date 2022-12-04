<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><polygon points="2.93,2.93 1.87,3.99 8,10.12 8,13 10.88,13 12.38,14.5 5,14.5 5,16 13.88,16 16.01,18.13 17.07,17.07"/><polygon points="12,8 15,8 10,3 7.56,5.44 12,9.88"/></g></g></svg>