<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/></g><g><path d="M10,2L3.5,4.5v4.77c0,4.04,2.77,7.81,6.5,8.73c3.73-0.92,6.5-4.69,6.5-8.73V4.5L10,2z M15,9.27c0,3.26-2.13,6.27-5,7.17 c-2.87-0.9-5-3.91-5-7.17V5.53l5-1.92l5,1.92V9.27z M10,6c-2.21,0-4,1.79-4,4c0,2.21,1.79,4,4,4s4-1.79,4-4C14,7.79,12.21,6,10,6z M11.15,11.85L9.5,10.21V8h1v1.79l1.35,1.35L11.15,11.85z"/></g></svg>