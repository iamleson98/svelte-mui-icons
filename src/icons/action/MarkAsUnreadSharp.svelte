<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><g><rect fill={color} height={size} width={size}/></g></g><g><g><polygon points="12.5,5.5 16.08,5.5 8.5,2 2,5 2,14 3.5,14 3.5,5.96 8.5,3.65"/><path d="M18,7H5v10h13V7z M16.5,10.22l-5,2.78l-5-2.78V8.5l5,2.78l5-2.78V10.22z"/></g></g></svg>