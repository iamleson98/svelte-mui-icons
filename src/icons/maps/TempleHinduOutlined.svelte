<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M16.5 9v2H15l-3-8V1h-1.5v2h-1V1H8v2l-3 8H3.5V9H2v9h7v-4h2v4h7V9h-1.5zm-4.41-1.5.75 2H7.16l.75-2h4.18zM8.48 6l.56-1.5h1.92l.56 1.5H8.48zm8.02 10.5h-4v-4h-5v4h-4v-4h2.54L6.6 11h6.8l.56 1.5h2.54v4z"/></g></svg>