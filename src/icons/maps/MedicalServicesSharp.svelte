<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M13,6V3H7v3H3v11h14V6H13z M8,4h4v2H8V4z M12.5,12h-2v2h-1v-2h-2v-1h2V9h1v2h2V12z"/></g></g></svg>