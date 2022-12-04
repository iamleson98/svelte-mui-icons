<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><rect height="1.5" width={size} x="3" y="5"/><rect height="1.5" width={size} x="3" y="11"/><rect height="1.5" width={size} x="3" y="8"/><path d="M18,5h-4v6.21C13.69,11.08,13.36,11,13,11c-1.38,0-2.5,1.12-2.5,2.5c0,1.38,1.12,2.5,2.5,2.5s2.5-1.12,2.5-2.5v-7H18V5z"/></g></g></svg>