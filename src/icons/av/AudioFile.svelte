<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M12,2H5.5C4.67,2,4,2.67,4,3.5v13C4,17.33,4.67,18,5.5,18h9c0.83,0,1.5-0.67,1.5-1.5V6L12,2z M13.5,11H11v3 c0,1.1-0.9,2-2,2s-2-0.9-2-2c0-1.1,0.9-2,2-2c0.37,0,0.7,0.11,1,0.28V9h3.5V11z M11,7V3l4,4H11z"/></g></svg>