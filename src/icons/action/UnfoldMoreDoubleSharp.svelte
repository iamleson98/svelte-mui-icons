<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><polygon points="6.63,7.37 7.69,8.43 10,6.12 12.31,8.43 13.37,7.37 10,4"/><polygon points="6.63,3.37 7.69,4.43 10,2.12 12.31,4.43 13.37,3.37 10,0"/><polygon points="13.37,16.63 12.31,15.57 10,17.88 7.69,15.57 6.63,16.63 10,20"/><polygon points="13.37,12.63 12.31,11.57 10,13.88 7.69,11.57 6.63,12.63 10,16"/></g></g></svg>