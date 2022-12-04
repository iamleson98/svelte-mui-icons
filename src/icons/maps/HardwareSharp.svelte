<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} y="0"/></g><g><g><rect height="6.25" width="4.5" x="7.5" y="10.75"/><path d="M14.5,3L12,5.5V3H8C5.79,3,4,4.79,4,7h3.5v2.25H12V6.5L14.5,9H16V3H14.5z"/></g></g></svg>