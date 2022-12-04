<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><g><path d="M17,3H3v14h14V3z M7,15.5H4.5v-11H6V12h1V15.5z M12,15.5H8V12h1V4.5h2V12h1V15.5z M15.5,15.5H13V12h1V4.5h1.5V15.5z"/></g></svg>