<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 24 24" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/><rect fill={color} height={size} width={size}/><rect fill={color} height={size} width={size}/></g><g><path d="M4,18l8.5-6L4,6V18z M13,6v12l8.5-6L13,6z"/></g></svg>