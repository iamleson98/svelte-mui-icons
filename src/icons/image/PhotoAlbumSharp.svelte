<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><g><path d="M16,2H4v16h12V2z M9,4h4v6l-2-1l-2,1V4z M6,15l2.12-2.83L9.5,14l1.88-2.5L14,15H6z"/></g></g></g></svg>