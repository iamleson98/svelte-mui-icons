<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M18,4H2v12h16V4z M9.5,13.5h-3v-3h3V13.5z M9.5,9.5h-3v-3h3V9.5z M13.5,13.5h-3v-3h3V13.5z M13.5,9.5h-3v-3h3V9.5z"/></g></g></svg>