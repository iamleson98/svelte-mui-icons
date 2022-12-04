<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/></g><g><path d="M12,2H5.5C4.67,2,4,2.67,4,3.5v13C4,17.33,4.67,18,5.5,18h9c0.83,0,1.5-0.67,1.5-1.5V6L12,2z M5.5,16.5v-13H11V7h3.5v9.5 H5.5z M10,9h3.5v2H11v3c0,1.1-0.9,2-2,2s-2-0.9-2-2c0-1.1,0.9-2,2-2c0.37,0,0.7,0.11,1,0.28V9z"/></g></svg>