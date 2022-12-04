<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 24 24" height={size} {viewBox} width={size}><g><path d="M0,0h24v24H0V0z" fill={color}/></g><g><path d="M19,19V3H5v16H3v2h18v-2H19z M15,13h-2v-2h2V13z"/></g></svg>