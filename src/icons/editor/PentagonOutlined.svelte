<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/></g><g><path d="M10,3.82l6.21,4.27l-2.57,7.41H6.37L3.79,8.09L10,3.82 M2,7.5L5.3,17h9.4L18,7.5L10,2L2,7.5z"/></g></svg>