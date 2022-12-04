<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M11.75,7h-3.5C7.31,7,6.61,7.85,6.77,8.77L8.5,18h3l1.73-9.23C13.39,7.85,12.69,7,11.75,7z"/><circle cx="10" cy="3.75" r="1.75"/></g></g></svg>