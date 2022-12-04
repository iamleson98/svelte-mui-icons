<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M17,10l-3.55,4.44C13.17,14.79,12.73,15,12.28,15H10.5v-1.5h1.78l2.8-3.5l-2.8-3.5H5.5v2H4v-2C4,5.67,4.67,5,5.5,5h6.78 c0.46,0,0.89,0.21,1.17,0.56L17,10z M9,12H7v-2H5.5v2h-2v1.5h2v2H7v-2h2V12z"/></svg>