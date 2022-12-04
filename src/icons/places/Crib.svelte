<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M16,12V9.5C16,8.67,15.33,8,14.5,8H10V4H7C5.34,4,4,5.34,4,7v5c0,0.83,0.67,1.5,1.5,1.5H7v2.27 c-0.59-0.31-1.13-0.7-1.59-1.17l-1.06,1.06C5.79,17.1,7.79,18,10,18c2.21,0,4.21-0.9,5.66-2.34l-1.06-1.06 c-0.47,0.47-1,0.86-1.59,1.17l0-2.27h1.5C15.33,13.5,16,12.83,16,12z M11.5,16.33c-0.48,0.11-0.98,0.17-1.5,0.17 s-1.02-0.06-1.5-0.17V13.5h3V16.33z"/></svg>