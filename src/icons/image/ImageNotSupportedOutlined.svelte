<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} y="0"/><path d="M17.07,17.07L2.93,2.93L2.22,3.64L4,5.41V15c0,0.55,0.45,1,1,1h9.59l1.78,1.78L17.07,17.07z M5,15V6.41l5.41,5.41 l-1.05,1.32L8,11.33L6,14h6.59l1,1H5z M6.41,5l-1-1H15c0.55,0,1,0.45,1,1v9.59l-1-1V5H6.41z"/></g></svg>