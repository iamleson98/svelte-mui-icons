<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M10.5,8h1v4h-1v-1.5h-1V12h-1V8h1v1.5h1V8z M7,8v2.5H5V12H4V8H7z M6,9H5v0.5h1V9z M16,8v2.5h-2V12h-1V8H16z M15,9h-1v0.5h1 V9z"/></g></svg>