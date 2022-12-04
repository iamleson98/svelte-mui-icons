<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M7.38,6.5v7h5.25v-7H7.38z M11.12,12H8.88V8h2.25V12z M1.5,12h3v-1.25h-3V6.5H6V8H3v1.25h3v4.25H1.5V12z M14,12h3v-1.25h-3 V6.5h4.5V8h-3v1.25h3v4.25H14V12z"/></g></svg>