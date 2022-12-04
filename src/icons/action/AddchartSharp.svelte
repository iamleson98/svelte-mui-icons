<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 24 24" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/><path d="M11,9h2v8h-2V9z M9,17v-6H7v6H9z M19,19H5V5h6V3H3v18h18v-8h-2V19z M15,13v4h2v-4H15z M19,5V2h-2v3h-3v2h3v3h2V7h3V5H19z"/></g><g/></svg>