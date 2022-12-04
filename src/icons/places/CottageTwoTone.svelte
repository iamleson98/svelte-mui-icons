<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><polygon opacity=".3" points="14.5,15.5 10.75,15.5 10.75,12.5 9.25,12.5 9.25,15.5 5.5,15.5 5.5,8.82 10,5.39 14.5,8.82"/><path d="M10,3.5L5.5,6.94V5.5H4v2.58L1.75,9.8l0.91,1.19L4,9.97V17h12V9.97l1.34,1.02l0.91-1.19L10,3.5z M14.5,15.5h-3.75v-3h-1.5v3 H5.5V8.82L10,5.39l4.5,3.44V15.5z M8.5,1.5c0,0.9-0.6,2.25-2.25,2.25C5.91,3.76,5.5,3.9,5.5,4.5H4c0-0.9,0.6-2.25,2.25-2.25 C6.59,2.24,7,2.1,7,1.5H8.5z"/></svg>