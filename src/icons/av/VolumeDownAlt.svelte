<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size} x="0"/><path d="M3,8v4h3l4,4V4L6,8H3z M11.5,13.15v-6.3c1.18,0.56,2,1.76,2,3.15S12.68,12.59,11.5,13.15z"/></svg>