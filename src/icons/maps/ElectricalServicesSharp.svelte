<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><polygon points="5,9 10,9 10,4 5,4 5,5 9,5 9,8 4,8 4,13.5 7,13.5 7,12.5 5,12.5"/><rect height={size} width={size} x="14" y="11"/><rect height={size} width={size} x="14" y="14"/><polygon points="9,12 8,12 8,14 9,14 9,16 13,16 13,10 9,10"/></g></g></svg>