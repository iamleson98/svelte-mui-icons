<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M6,12H5V9H4V8h2V12z M11,11H9v-0.5h2V8H8v1h2v0.5H8V12h3V11z M15.5,12V8h-3v1h2v0.5h-1v1h1V11h-2v1H15.5z"/></g></svg>