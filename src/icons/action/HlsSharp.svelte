<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M6,8h1v4H6v-1.5H5V12H4V8h1v1.5h1V8z M13,12h3V9.75h-2V9h1v0.25h1V8h-3v2.25h2V11h-1v-0.25h-1V12z M11.5,11H10V8H9v4l2.5,0 V11z"/></g></svg>