<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 24 24" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M3,9H1v11c0,1.11,0.89,2,2,2h17v-2H3V9z"/><path d="M18,5V3c0-1.1-0.9-2-2-2h-4c-1.1,0-2,0.9-2,2v2H5v11c0,1.1,0.9,2,2,2h14c1.1,0,2-0.9,2-2V5H18z M12,3h4v2h-4V3z M21,16H7 V7h14V16z"/></g></g></svg>