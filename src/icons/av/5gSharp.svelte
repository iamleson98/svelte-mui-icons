<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><polygon points="12,10.5 14,10.5 14,12 11,12 11,8 15,8 15,7 10,7 10,13 15,13 15,9.5 12,9.5"/></g><g><polygon points="9,8 6,8 6,9.5 9,9.5 9,13 5,13 5,12 8,12 8,10.5 5,10.5 5,7 9,7"/></g></g></svg>