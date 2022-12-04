<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><polygon points="5,14.94 6.06,16 10,12.06 13.94,16 15,14.94 10,9.94"/><polygon points="5,9 6.06,10.06 10,6.12 13.94,10.06 15,9 10,4"/></g></g></svg>