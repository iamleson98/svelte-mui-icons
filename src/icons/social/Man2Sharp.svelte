<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><g><circle cx="10" cy="3.75" r="1.75"/><path d="M13,7H7v6h2v5h2v-5h2V7z"/></g></g></g></svg>