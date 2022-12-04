<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/></g><g><g><g><path d="M4,14.59V4h12v5h1V4c0-0.55-0.45-1-1-1H4C3.45,3,3,3.45,3,4v13l3-3h7v-1H5.59L4,14.59z"/></g><g><polygon points="18,13 16.4,13 17.64,10 14,10 14,14.36 15.45,14.36 15.45,18"/></g></g></g></svg>