<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M18,6.5C18,5.12,14.42,4,10,4S2,5.12,2,6.5c0,1.3,3.18,2.37,7.25,2.49v3.51H7.61c-0.58,0-1.11,0.33-1.35,0.86l-0.8,1.67 C5.25,15.48,5.58,16,6.08,16h0c0.26,0,0.49-0.15,0.61-0.38L7.5,14h5l0.81,1.62c0.12,0.23,0.35,0.38,0.61,0.38h0 c0.5,0,0.83-0.52,0.62-0.97l-0.8-1.67c-0.25-0.52-0.78-0.86-1.35-0.86h-1.64V8.99C14.82,8.87,18,7.8,18,6.5z"/></g></g></svg>