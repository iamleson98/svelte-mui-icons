<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><g><path d="M18,13h-1v-1c0-0.82-0.67-1.5-1.5-1.5S14,11.18,14,12v1h-1v4h5V13z M14.75,12c0-0.41,0.34-0.75,0.75-0.75 c0.41,0,0.75,0.34,0.75,0.75v1h-1.5V12z M12,15l-2,2l-4.24-4.24L0,7.01C2.6,4.53,6.12,3,10,3c3.88,0,7.4,1.53,10,4.01L17.51,9.5H15 c-1.66,0-3,1.34-3,3V15z"/></g></svg>