<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/><path d="M10,15H4V6.18L10,10l6-3.82V10h1V5c0-0.55-0.45-1-1-1H4C3.45,4,3,4.45,3,5v10c0,0.55,0.45,1,1,1h6L10,15z M16,5l-6,3.82 L4,5H16z M13.76,17l-2.12-2.12l0.71-0.71l1.41,1.41l3.54-3.54L18,12.76L13.76,17z"/></g></svg>