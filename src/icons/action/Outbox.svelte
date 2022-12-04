<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" height={size} {viewBox} width={size}><path d="M0 0h20v20H0V0z" fill={color}/><path d="M7.5 13c0 1.38 1.12 2.5 2.5 2.5s2.5-1.12 2.5-2.5H16V4H4v9h3.5zM4 2h12c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2zm2 7h2v3h4V9h2l-4-4-4 4z"/></svg>