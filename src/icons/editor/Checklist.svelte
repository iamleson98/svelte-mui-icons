<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M18,7.5h-7V6h7V7.5z M18,12.5h-7V14h7V12.5z M3.06,5.11L2,6.17L4.83,9l4.6-4.6L8.36,3.34L4.83,6.88L3.06,5.11z M3.06,11.61 L2,12.67l2.83,2.83l4.6-4.6L8.36,9.84l-3.54,3.54L3.06,11.61z"/></svg>