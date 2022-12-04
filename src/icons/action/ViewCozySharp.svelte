<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M18,4H2v12h16V4z M9.25,13.75h-3v-3h3V13.75z M9.25,9.25h-3v-3h3V9.25z M13.75,13.75h-3v-3h3V13.75z M13.75,9.25h-3v-3h3 V9.25z"/></g></g></svg>