<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/></g><g><path d="M16.27,10l-3.14,5.5H6.87L3.73,10l3.14-5.5h6.26L16.27,10z M6,3l-4,7l4,7h8l4-7l-4-7H6z"/></g></svg>