<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M2.53,5.47c-0.29,0.29-0.29,0.77,0,1.06L9,13H4.75C4.34,13,4,13.34,4,13.75c0,0.41,0.34,0.75,0.75,0.75h10.5 c0.41,0,0.75-0.34,0.75-0.75S15.66,13,15.25,13H11l4.18-4.18C15.43,8.94,15.71,9,16,9c1.1,0,2-0.9,2-2s-0.9-2-2-2s-2,0.9-2,2 c0,0.26,0.05,0.51,0.14,0.74L10,11.88L3.59,5.47C3.3,5.18,2.82,5.18,2.53,5.47z"/></g></svg>