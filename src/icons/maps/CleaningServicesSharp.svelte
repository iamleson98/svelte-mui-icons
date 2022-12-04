<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M16,9h-4V3H8v6H4v8h12V9z M15,16h-2v-2h-1v2h-1.5v-2h-1v2H8v-2H7v2H5v-6h10V16z"/></g></svg>