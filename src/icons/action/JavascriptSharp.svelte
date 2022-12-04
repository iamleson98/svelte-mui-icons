<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M10.5,10.75h1V11h1v-0.75h-2V8h3v1.25h-1V9h-1v0.75h2V12h-3V10.75z M8,8v3H7v-1H6v2h3V8H8z"/></g></svg>