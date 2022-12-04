<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" height={size} {viewBox} width={size}><path d="M0 0h20v20H0z" fill={color}/><path d="M13.3 2L18 6.7v6.6L13.3 18H6.7L2 13.3V6.7L6.7 2h6.6zm.7 5l-1-1-3 3-3-3-1 1 3 3-3 3 1 1 3-3 3 3 1-1-3-3 3-3z"/></svg>