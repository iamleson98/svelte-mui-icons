<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} y="0"/></g><g><g><path d="M18,2H2v6h1v10h14V8h1V2z M16.5,6.5h-13v-3h13V6.5z M12,11.5H8V10h4V11.5z"/></g></g></svg>