<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><polygon points="14,14 18,10 14,6 12.94,7.06 15.13,9.25 8,9.25 8,10.75 15.13,10.75 12.94,12.94"/><polygon points="15.5,15.5 4.5,15.5 4.5,4.5 15.5,4.5 15.5,6 17,6 17,3 3,3 3,17 17,17 17,14 15.5,14"/></g></g></svg>