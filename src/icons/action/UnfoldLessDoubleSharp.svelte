<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><polygon points="13.37,1.06 12.31,0 10,2.31 7.69,0 6.63,1.06 10,4.43"/><polygon points="13.37,5.06 12.31,4 10,6.31 7.69,4 6.63,5.06 10,8.43"/><polygon points="6.63,14.94 7.69,16 10,13.69 12.31,16 13.37,14.94 10,11.57"/><polygon points="6.63,18.94 7.69,20 10,17.69 12.31,20 13.37,18.94 10,15.57"/></g></g></svg>