<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M4,4v12h12V4H4z M15,15H5V7h10V15z"/><polygon points="13.18,9.23 12.47,8.53 8.94,12.06 7.53,10.65 6.82,11.35 8.94,13.47"/></g></g></svg>