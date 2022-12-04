<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><rect height={size} opacity=".3" width={size} x="4" y="9"/><path d="M16,8V6c0-0.55-0.45-1-1-1H5C4.45,5,4,5.45,4,6v2C3.45,8,3,8.45,3,9v4h1l0.75,2h0.5L6,13h8l0.75,2h0.5L16,13h1V9 C17,8.45,16.55,8,16,8z M10.5,6H15v2h-4.5V6z M5,6h4.5v2H5V6z M16,12H4V9h12V12z"/></g></g></svg>