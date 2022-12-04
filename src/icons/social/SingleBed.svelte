<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M15,8V6c0-0.55-0.45-1-1-1H6C5.45,5,5,5.45,5,6v2C4.45,8,4,8.45,4,9v4h1l0.75,2h0.5L7,13h6l0.75,2h0.5L15,13h1V9 C16,8.45,15.55,8,15,8z M10.5,6H14v2h-3.5V6z M6,6h3.5v2H6V6z M15,12H5V9h10V12z"/></g></g></svg>