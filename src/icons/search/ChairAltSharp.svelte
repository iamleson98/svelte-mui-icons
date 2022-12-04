<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 24 24" height={size} {viewBox} width={size}><g><path d="M0,0h24v24H0V0z" fill={color}/></g><g><path d="M16,10h3V3H5v7h3v2H5v9h2v-3h10v3h2v-9h-3V10z M7,8V5h10v3H7z M17,16H7v-2h10V16z M14,12h-4v-2h4V12z"/></g></svg>