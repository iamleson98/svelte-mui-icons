<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/></g><g><path d="M8,7.32L5.5,8.89v1.77L8,9.09v1.77l-2.5,1.57v1.77L8,12.63V17h1.5c3.04,0,5.5-2.46,5.5-5.5h-1.5c0,2.21-1.79,4-4,4v-3.81 l3-1.88V8.04l-3,1.88V8.15l3-1.88V4.5l-3,1.88V3H8V7.32z"/></g></svg>