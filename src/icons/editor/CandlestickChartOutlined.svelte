<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/></g><g><g><path d="M7.25,3h-1.5v2H4v10h1.75v2h1.5v-2H9V5H7.25V3z M7.5,6.5v7h-2v-7H7.5z"/><path d="M14.25,7V3h-1.5v4H11v6h1.75v4h1.5v-4H16V7H14.25z M14.5,11.5h-2v-3h2V11.5z"/></g></g></svg>