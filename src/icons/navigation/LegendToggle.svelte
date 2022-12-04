<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/><path d="M16,15H4v-1h12V15z M16,11H4v1h12V11z M4,9l4-2.78L12,9l4-2.78V5l-4,2.78L8,5L4,7.78L4,9z"/></g></svg>