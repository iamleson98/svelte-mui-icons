<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M18,4H2v12h16V4z M13.01,11.57L3.5,9.24V8.5h13v0.15L13.01,11.57z M16.5,7h-13V5.5h13V7z"/></g></svg>