<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><polygon points="13,10.5 13,17 18,13.75"/><rect height="1.5" width={size} x="3" y="5"/><rect height="1.5" width={size} x="3" y="11.25"/><rect height="1.5" width={size} x="3" y="8.12"/></g></g></svg>