<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M7.5,11.3L12,5H2l4.5,6.3V15H5v1h4v-1H7.5V11.3z M5.37,8L3.94,6h6.11L8.63,8H5.37z"/><path d="M15,5h-1v7.28C13.7,12.11,13.37,12,13,12c-1.1,0-2,0.9-2,2c0,1.1,0.9,2,2,2s2-0.9,2-2V7h2V5H15z"/></g></g></svg>