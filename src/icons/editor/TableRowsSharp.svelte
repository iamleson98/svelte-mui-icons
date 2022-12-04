<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size} x="0" y="0"/><path d="M17,7H3V4h14V7z M17,8.5H3v3h14V8.5z M17,13H3v3h14V13z"/></svg>