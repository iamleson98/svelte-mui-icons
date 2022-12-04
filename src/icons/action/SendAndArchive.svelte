<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" height={size} {viewBox} width={size}><path d="M0 0h20v20H0V0z" fill={color}/><path d="M18 8h-3.5L1 2v6l8 2-8 2v6l7-3v3c0 1.1.9 2 2 2h8c1.1 0 2-.9 2-2v-8c0-1.1-.9-2-2-2zm0 10h-8v-8h8v8zm-4-1l-3-3.5h2V11h2v2.5h2L14 17z"/></svg>