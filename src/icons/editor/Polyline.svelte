<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><polygon points="12.5,13.5 12.5,14.49 7.5,11.78 7.5,9.24 9.83,6.5 13,6.5 13,2 8.5,2 8.5,5.75 6.16,8.5 3,8.5 3,13 6.6,13 12.5,16.2 12.5,18 17,18 17,13.5"/></g></svg>