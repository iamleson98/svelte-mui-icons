<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M10,2L3.5,4.5v4.77c0,4.04,2.77,7.81,6.5,8.73c3.73-0.92,6.5-4.69,6.5-8.73V4.5L10,2z M10,14c-2.21,0-4-1.79-4-4 c0-2.21,1.79-4,4-4s4,1.79,4,4C14,12.21,12.21,14,10,14z M11.15,11.85L9.5,10.21V8h1v1.79l1.35,1.35L11.15,11.85z"/></g></svg>