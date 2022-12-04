<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} y="0"/></g><g><path d="M18,6c0-1.66-1.34-3-3-3H5C3.34,3,2,4.34,2,6c0,1.3,0.84,2.4,2,2.82v6.68C4,16.33,4.67,17,5.5,17h9 c0.83,0,1.5-0.67,1.5-1.5l0-6.68C17.16,8.4,18,7.3,18,6z M12.71,11.71l-2,2c-0.39,0.39-1.02,0.39-1.41,0l-2-2 c-0.39-0.39-0.39-1.02,0-1.41l2-2c0.39-0.39,1.02-0.39,1.41,0l2,2C13.1,10.68,13.1,11.32,12.71,11.71z"/></g></svg>