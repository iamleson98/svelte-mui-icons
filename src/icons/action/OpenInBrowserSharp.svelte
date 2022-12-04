<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" height={size} {viewBox} width={size}><path d="M0 0h24v24H0V0z" fill={color}/><path d="M3 4v16h6v-2H5V8h14v10h-4v2h6V4H3zm9 6l-4 4h3v6h2v-6h3l-4-4z"/></svg>