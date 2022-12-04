<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/></g><g><path d="M5.5,7.5C5.5,5.01,7.51,3,10,3s4.5,2.01,4.5,4.5V16H13V7.5c0-1.66-1.34-3-3-3s-3,1.34-3,3l0,2.63l1.19-1.19L9.25,10l-3,3 l-3-3l1.06-1.06l1.19,1.19L5.5,7.5z"/></g></svg>