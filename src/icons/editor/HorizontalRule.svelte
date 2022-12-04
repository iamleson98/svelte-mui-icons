<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/><rect height={size} width={size} x="4" y="9"/></g><g><rect fill={color} height={size} width={size}/><rect height={size} width={size} x="3" y="9"/></g></svg>