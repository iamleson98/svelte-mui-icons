<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M10.75,8H15l2-2.25L15,3.5h-4.25V2h-1.5v1.5H4V8h5.25v1.5H5l-2,2.25L5,14h4.25v4h1.5v-4H16V9.5h-5.25V8z"/></g></svg>