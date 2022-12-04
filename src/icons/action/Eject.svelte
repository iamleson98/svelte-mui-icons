<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" height={size} {viewBox} width={size}><path d="M0 24V0h24v24H0z" fill={color}/><path d="M5 17h14v2H5zm7-12L5.33 15h13.34z"/></svg>