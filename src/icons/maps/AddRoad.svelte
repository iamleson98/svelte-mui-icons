<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><rect height={size} width={size} x="4" y="4"/><rect height={size} width={size} x="15" y="4"/><rect height={size} width={size} x="9.5" y="4"/><rect height={size} width={size} x="9.5" y="14"/><polygon points="18,15 16,15 16,13 15,13 15,15 13,15 13,16 15,16 15,18 16,18 16,16 18,16"/><rect height={size} width={size} x="9.5" y="9"/></g></g></svg>