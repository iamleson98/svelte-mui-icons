<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><polygon points="2,15 2,18 4,18 4,16.5 9,16.5 9,18 11,18 11,16.5 16,16.5 16,18 18,18 18,15"/><path d="M15 2H5c-.28 0-.5.22-.5.5v10c0 .28.22.5.5.5h10c.28 0 .5-.22.5-.5v-10c0-.28-.22-.5-.5-.5zm-2.5 4.5h-5V5h5v1.5z"/></g></g></svg>