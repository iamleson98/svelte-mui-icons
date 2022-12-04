<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 24 24" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/><g><path d="M19,1H5v22h14V1z M17,19H7V5h10V19z"/><rect height={size} width={size} x="8" y="6"/></g></g></svg>