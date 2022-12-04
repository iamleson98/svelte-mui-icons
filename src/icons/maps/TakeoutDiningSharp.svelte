<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><polygon points="5.5,16 14.5,16 14.8,10 5.2,10"/><polygon points="16.44,5.5 14.95,6.99 15,6 12,3 8,3 5,6 5.05,6.99 3.56,5.5 2.5,6.56 4.94,9 15.06,9 17.5,6.56"/></g></g></svg>