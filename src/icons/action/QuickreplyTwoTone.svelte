<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><g opacity=".3"><polygon points="4,4 4,14.59 5.59,13 13,13 13,9 16,9 16,4"/></g><path d="M5.59,13L4,14.59V4h12v5h1V4c0-0.55-0.45-1-1-1H4C3.45,3,3,3.45,3,4v13l3-3h7v-1H5.59z"/><g><polygon points="16.4,13 17.64,10 14,10 14,14.36 15.45,14.36 15.45,18 18,13"/></g></g></g></svg>