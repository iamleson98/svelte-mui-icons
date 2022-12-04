<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M15 10.75c-2.21 0-4 1.79-4 4s1.79 4 4 4 4-1.79 4-4-1.79-4-4-4zm2 4.5h-1.5v1.5h-1v-1.5H13v-1h1.5v-1.5h1v1.5H17v1z"/><rect height="1.5" width={size} x="5.5" y="5"/><path d="M5.5 13.5V15h4.01c0-.08-.01-.17-.01-.25 0-.43.05-.85.15-1.25H5.5zM15 9.25H5.5v1.5h5.74c.98-.93 2.3-1.5 3.76-1.5z"/><circle cx="3" cy="5.75" r="1"/><circle cx="3" cy="14.25" r="1"/><circle cx="3" cy="10" r="1"/></g></g></svg>