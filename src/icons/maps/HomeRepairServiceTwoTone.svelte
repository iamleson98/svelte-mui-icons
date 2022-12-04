<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><g><path d="M16,7h-3V5c0-0.55-0.45-1-1-1H8C7.45,4,7,4.45,7,5v2H4C3.45,7,3,7.45,3,8v8h14V8C17,7.45,16.55,7,16,7z M8,5h4v2H8V5z M16,15H4v-3h2v1h1v-1h6v1h1v-1h2V15z M16,11h-2v-1h-1v1H7v-1H6v1H4V8h3h6h3V11z"/></g><g opacity=".3"><polygon points="7,8 4,8 4,11 6,11 6,10 7,10 7,11 13,11 13,10 14,10 14,11 16,11 16,8 13,8"/></g><g opacity=".3"><polygon points="14,13 13,13 13,12 7,12 7,13 6,13 6,12 4,12 4,15 16,15 16,12 14,12"/></g></g></g></svg>