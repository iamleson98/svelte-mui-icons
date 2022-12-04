<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/></g><g><g><polygon points="11,10 8,7 8,9.5 3,9.5 3,10.5 8,10.5 8,13"/><rect height={size} width={size} x="11" y="7"/><rect height={size} width={size} x="11" y="12"/><rect height={size} width={size} x="13" y="9.5"/></g></g></svg>