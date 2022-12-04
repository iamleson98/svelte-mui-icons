<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M15.5 1v1.5h-11V1H3v18h1.5v-1.5h11V19H17V1h-1.5zm0 3v5.25H11v-3.5H6v3.5H4.5V4h11zM14 16v-3.5H9V16H4.5v-5.25h11V16H14z"/></g></svg>