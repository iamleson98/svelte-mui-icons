<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 24 24" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><polygon points="20,8 15,8 15,10 18,10 18,21 6,21 6,10 9,10 9,8 4,8 4,23 20,23"/><polygon points="11,16 13,16 13,5 16,5 12,1 8,5 11,5"/></g></g></svg>