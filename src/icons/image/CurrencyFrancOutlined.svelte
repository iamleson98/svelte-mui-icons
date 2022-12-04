<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/></g><g><polygon points="14.5,4.5 14.5,3 6,3 6,13 4.5,13 4.5,14.5 6,14.5 6,17 7.5,17 7.5,14.5 11,14.5 11,13 7.5,13 7.5,10.5 14,10.5 14,9 7.5,9 7.5,4.5"/></g></svg>