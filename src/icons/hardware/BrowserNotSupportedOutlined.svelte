<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/></g><g><g><path d="M15,5v8.59l1,1V5c0-0.55-0.45-1-1-1H5.41l1,1H15z"/><path d="M3.64,3.64L2.93,4.34L4,5.41V15c0,0.55,0.45,1,1,1h9.59l1.07,1.07l0.71-0.71L3.64,3.64z M5,15V6.41L13.59,15H5z"/></g></g></svg>