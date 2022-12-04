<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/><path d="M3,4v12h14V4H3z M16,7.67h-2.5V5H16V7.67z M13.5,8.67H16v2.67h-2.5V8.67z M4,5h8.5v10H4V5z M13.5,15v-2.67H16V15H13.5z"/></g></svg>