<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><polygon points="10,6 8,4 6.12,4 18,15.88 18,6"/><polygon points="2.22,2.22 1.16,3.28 2,4.12 2,16 13.88,16 16.72,18.84 17.78,17.78"/></g></g></svg>