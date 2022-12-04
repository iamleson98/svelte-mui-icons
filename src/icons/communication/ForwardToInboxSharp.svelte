<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/><path d="M15,12.5l3,3l-3,3V16h-3v-1h3V12.5z M11,16H3V4h14v8h-1V6.18L10,10L4,6.18V15h7L11,16z M4,5l6,3.82L16,5H4z"/></g></svg>