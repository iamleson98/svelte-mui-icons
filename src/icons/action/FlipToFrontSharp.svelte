<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" height={size} {viewBox} width={size}><path d="M0 0h24v24H0V0z" fill={color}/><path d="M3 13h2v-2H3v2zm0 4h2v-2H3v2zm0-8h2V7H3v2zm12 12h2v-2h-2v2zm6-18H7v14h14V3zm-2 12H9V5h10v10zm-8 6h2v-2h-2v2zm-4 0h2v-2H7v2zm-4 0h2v-2H3v2z"/></svg>