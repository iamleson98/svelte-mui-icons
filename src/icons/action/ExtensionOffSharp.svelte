<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M17.07,17.07L2.93,2.93L1.87,3.99L3,5.12V8c1.1,0,2,0.9,2,2s-0.9,2-2,2v5h5c0-1.1,0.9-2,2-2s2,0.9,2,2h2.88l1.13,1.13 L17.07,17.07z M19,10c0,1.1-0.9,2-2,2v2.88L5.12,3H8c0-1.1,0.9-2,2-2s2,0.9,2,2h5v5C18.1,8,19,8.9,19,10z"/></svg>