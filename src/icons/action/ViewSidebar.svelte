<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/><path d="M17,7.33h-3V4h3V7.33z M17,12.67h-3V16h3V12.67z M17,8.33h-3v3.33h3V8.33z M13,4H3v12h10V4z"/></g></svg>