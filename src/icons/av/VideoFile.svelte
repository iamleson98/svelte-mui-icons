<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M12,2H5.5C4.67,2,4,2.67,4,3.5v13C4,17.33,4.67,18,5.5,18h9c0.83,0,1.5-0.67,1.5-1.5V6L12,2z M13,14 c0,0-0.78-0.55-1.5-1.05V14c0,0.28-0.22,0.5-0.5,0.5H7.5C7.22,14.5,7,14.28,7,14v-3.5C7,10.22,7.22,10,7.5,10H11 c0.28,0,0.5,0.22,0.5,0.5v1.05L13,10.5V14z M11,7V3l4,4H11z"/></g></svg>