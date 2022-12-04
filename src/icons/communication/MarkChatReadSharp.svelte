<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/><path d="M13.76,15l-2.12-2.12l0.71-0.71l1.41,1.41l3.54-3.54L18,10.76L13.76,15z M10,13c0-2.76,2.24-5,5-5c0.71,0,1.39,0.15,2,0.42 V3H3v14l3-3h4.1C10.04,13.68,10,13.34,10,13z"/></g></svg>