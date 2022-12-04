<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><rect height="4.75" opacity=".3" width="4.75" x="10.75" y="10.75"/><rect height="4.75" opacity=".3" width="4.75" x="4.5" y="10.75"/><rect height="4.75" opacity=".3" width="4.75" x="4.5" y="4.5"/><rect height="4.75" opacity=".3" width="4.75" x="10.75" y="4.5"/><path d="M15.5 3h-11C3.67 3 3 3.67 3 4.5v11c0 .83.67 1.5 1.5 1.5h11c.83 0 1.5-.67 1.5-1.5v-11c0-.83-.67-1.5-1.5-1.5zM9.25 15.5H4.5v-4.75h4.75v4.75zm0-6.25H4.5V4.5h4.75v4.75zm6.25 6.25h-4.75v-4.75h4.75v4.75zm0-6.25h-4.75V4.5h4.75v4.75z"/></g></g></svg>