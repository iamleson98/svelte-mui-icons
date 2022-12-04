<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size} x="0"/><path d="M2.5,5v10H4V5H2.5z M17.5,10l-4,4l-1.06-1.06l2.19-2.19H5.5v-1.5h9.13l-2.19-2.19L13.5,6L17.5,10z"/></svg>