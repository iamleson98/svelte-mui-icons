<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><polygon points="13.5,7 6.5,7 5.56,9.5 14.44,9.5"/><path d="M12 3V1.75c0-.41-.34-.75-.75-.75s-.75.34-.75.75V3h-1V1.75c0-.41-.34-.75-.75-.75S8 1.34 8 1.75V3l-.94 2.5h5.88L12 3zm5.25 6c-.41 0-.75.34-.75.75V11h-13V9.75c0-.41-.34-.75-.75-.75S2 9.34 2 9.75V18h6v-2c0-1.1.9-2 2-2s2 .9 2 2v2h6V9.75c0-.41-.34-.75-.75-.75z"/></g></g></svg>