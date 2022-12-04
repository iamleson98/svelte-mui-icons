<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 24 24" height={size} {viewBox} width={size}><g><path d="M0,0h24v24H0V0z" fill={color}/></g><g><g><rect height={size} width={size} x="6" y="3"/><path d="M19,6H5v15h14V6z M16,15h-2.5v2.5h-3V15H8v-3h2.5V9.5h3V12H16V15z"/></g></g></svg>