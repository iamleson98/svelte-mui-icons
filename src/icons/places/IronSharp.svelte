<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M15,5.5v6h-1V6H6v2h1.5V7.5h5l0,1.5H5c-1.66,0-3,1.34-3,3v2.5h12V13h2.5V7H18V5.5H15z"/></svg>