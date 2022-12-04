<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M3,5h9v1.5H3V5z M3,11.25h6v1.5H3V11.25z M3,8.12h9v1.5H3V8.12z M12.07,17.02l1.94-1.95l1.94,1.95l1.07-1.07l-1.95-1.94 l1.95-1.94L15.95,11l-1.94,1.95L12.07,11L11,12.07l1.95,1.94L11,15.95L12.07,17.02z"/></g></svg>