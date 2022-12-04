<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><polygon points="4,8.5 2,8.5 2,11.5 4,11.5 4,16 8,16 8,14.5 5.5,14.5 5.5,10.25 3.5,10.25 3.5,9.75 5.5,9.75 5.5,5.5 8,5.5 8,4 4,4"/><polygon points="16,8.5 16,4 12,4 12,5.5 14.5,5.5 14.5,9.75 16.5,9.75 16.5,10.25 14.5,10.25 14.5,14.5 12,14.5 12,16 16,16 16,11.5 18,11.5 18,8.5"/></g></g></svg>