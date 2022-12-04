<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><rect height={size} opacity=".3" width={size} x="4.5" y="4.5"/><path d="M3,3v14h14V3H3z M15.5,15.5h-11v-11h11V15.5z"/></g></svg>