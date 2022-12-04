<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 24 24" height={size} {viewBox} width={size}><g><path d="M0,0h24v24H0V0z" fill={color}/></g><g><path d="M22,4H2v16h20V4z M13,6h2.5v12H13V6z M11,18H8.5V6H11V18z M4,6h2.5v12H4V6z M20,18h-2.5V6H20V18z"/></g></svg>