<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M8.5,12v-1.25h1V11h1v-0.75h-2V8h3v1.25h-1V9h-1v0.75h2V12H8.5z M16,12V9.75h-2V9h1v0.25h1V8h-3v2.25h2V11h-1v-0.25h-1V12 H16z M7,12v-1.25H6V11H5V9h1v0.25h1V8H4v4H7z"/></g></svg>