<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><polygon points="13,10 8,2 3,10 4.18,10 1,15 6.5,15 6.5,18 9.5,18 9.5,15 15,15 11.82,10"/><polygon points="15.82,10 17,10 12,2 10.59,4.26 14.8,11 13.64,11 16.19,15 19,15"/><rect height={size} width={size} x="10.5" y="16"/></g></g></svg>