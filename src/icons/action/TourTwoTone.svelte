<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 24 24" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/><g><polygon opacity=".3" points="7,12 7,6 18.05,6 16.85,9 18.05,12"/><g><path d="M21,4h-8h-1H7V2H5v2v10v8h2v-8h4h1h9l-2-5L21,4z M7,12V6h11.05l-1.2,3l1.2,3H7z M14,9c0,1.1-0.9,2-2,2s-2-0.9-2-2 s0.9-2,2-2S14,7.9,14,9z"/></g></g></g></svg>