<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/></g><g><g><polygon points="15,5.06 13.94,4 10,7.94 6.06,4 5,5.06 10,10.06"/><polygon points="15,11 13.94,9.94 10,13.88 6.06,9.94 5,11 10,16"/></g></g></svg>