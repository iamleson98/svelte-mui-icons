<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/></g><g><g><g><path d="M16,7h-3V5c0-0.55-0.45-1-1-1H8C7.45,4,7,4.45,7,5v2H4C3.45,7,3,7.45,3,8v8h14V8C17,7.45,16.55,7,16,7z M8,5h4v2H8V5z M16,15H4v-3h2v1h1v-1h6v1h1v-1h2V15z M14,11v-1h-1v1H7v-1H6v1H4V8h3h6h3v3H14z"/></g></g></g></svg>