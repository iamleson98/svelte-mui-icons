<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 24 24" height={size} {viewBox} width={size}><g><path d="M0,0h24v24H0V0z" fill={color}/></g><g><g><rect height={size} width={size} x="11" y="15"/><rect height={size} width={size} x="11" y="7"/><path d="M5.01,1v22H19V1H5.01z M17,18H7V6h10V18z"/></g></g></svg>