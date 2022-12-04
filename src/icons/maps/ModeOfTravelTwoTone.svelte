<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M16.48,8C16.23,4.64,13.42,2,10,2C6.41,2,3.5,4.91,3.5,8.5C3.5,12.84,10,18,10,18s1.28-1.01,2.7-2.52 c0.1,0.01,0.2,0.02,0.3,0.02c1.1,0,2-0.9,2-2s-0.9-2-2-2s-2,0.9-2,2c0,0.44,0.14,0.85,0.38,1.18c-0.49,0.51-0.97,0.97-1.38,1.35 C8.1,14.3,5,10.97,5,8.5c0-2.76,2.24-5,5-5c2.59,0,4.72,1.98,4.98,4.5h-2.73l3.5,3.5l3.5-3.5L16.48,8z"/></svg>