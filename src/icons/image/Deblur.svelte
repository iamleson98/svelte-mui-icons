<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><circle cx="5.5" cy="11.5" r=".75"/><circle cx="5.5" cy="14.5" r=".75"/><circle cx="5.5" cy="8.5" r=".75"/><circle cx="3" cy="8.5" r=".5"/><circle cx="5.5" cy="5.5" r=".75"/><circle cx="3" cy="11.5" r=".5"/><circle cx="8.5" cy="17" r=".5"/><circle cx="8.5" cy="3" r=".5"/><circle cx="8.5" cy="5.5" r=".75"/><circle cx="8.5" cy="11.5" r="1"/><circle cx="8.5" cy="8.5" r="1"/><circle cx="8.5" cy="14.5" r=".75"/><path d="M10,3v14c3.87,0,7-3.13,7-7C17,6.13,13.87,3,10,3z"/></g></g></svg>