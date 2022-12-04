<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M18,9.5h-3V4H5v5.5H2V16h16V9.5z M13.5,9.5h-7v-4h7V9.5z M14.75,13.5c-0.41,0-0.75-0.34-0.75-0.75 c0-0.41,0.34-0.75,0.75-0.75s0.75,0.34,0.75,0.75C15.5,13.16,15.16,13.5,14.75,13.5z"/></g></svg>