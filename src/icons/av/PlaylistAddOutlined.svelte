<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><rect height="1.5" width={size} x="3" y="5"/><rect height="1.5" width={size} x="3" y="11.25"/><rect height="1.5" width={size} x="3" y="8.12"/><polygon points="14.75,11.25 14.75,8 13.25,8 13.25,11.25 10,11.25 10,12.75 13.25,12.75 13.25,16 14.75,16 14.75,12.75 18,12.75 18,11.25"/></g></g></svg>