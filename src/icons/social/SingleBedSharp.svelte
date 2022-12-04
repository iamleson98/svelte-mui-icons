<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M15,8V5H5v3H4v5h1l0.75,2h0.5L7,13h6l0.75,2h0.5L15,13h1V8H15z M6,8V6h3.5v2H6z M10.5,8V6H14v2H10.5z"/></g></svg>