<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/></g><g><g/><g><path d="M10,14c1.86,0,3.41-1.28,3.86-3H6.14C6.59,12.72,8.14,14,10,14z"/><path d="M9.99,3C6.13,3,3,6.14,3,10s3.13,7,6.99,7c3.87,0,7.01-3.14,7.01-7S13.86,3,9.99,3z M9.99,16C6.69,16,4,13.31,4,10 s2.69-6,5.99-6C13.31,4,16,6.69,16,10S13.31,16,9.99,16z"/><circle cx="13" cy="8" r="1"/><circle cx="7" cy="8" r="1"/></g></g></svg>