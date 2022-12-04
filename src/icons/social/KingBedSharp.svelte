<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M16,8V5H4v3H3v5h1l0.75,2h0.5L6,13h8l0.75,2h0.5L16,13h1V8H16z M9.5,8H5V6h4.5V8z M15,8h-4.5V6H15V8z"/></g></svg>