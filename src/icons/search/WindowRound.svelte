<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><g><path d="M9.25 9.25V3H4.5C3.67 3 3 3.67 3 4.5v4.75h6.25z"/></g><g><path d="M10.75 9.25H17V4.5c0-.83-.67-1.5-1.5-1.5h-4.75v6.25z"/></g><g><path d="M10.75 10.75V17h4.75c.83 0 1.5-.67 1.5-1.5v-4.75h-6.25z"/></g><g><path d="M9.25 10.75H3v4.75c0 .83.67 1.5 1.5 1.5h4.75v-6.25z"/></g></g></g></svg>