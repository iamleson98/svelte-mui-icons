<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 24 24" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><g><path d="M16,11V5h6v6H16z M16,19h6v-6h-6V19z M14,5v14H2V5H14z M9.5,12c0-0.83-0.67-1.5-1.5-1.5S6.5,11.17,6.5,12s0.67,1.5,1.5,1.5 S9.5,12.83,9.5,12z"/></g></svg>