<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M16.5,10V5.5h-13v9H12c0.01,0.02,0,1.5,0,1.5H2V4h16v6H16.5z M15.75,11.5c-1.24,0-2.25,1.01-2.25,2.25s1,2.25,2.25,2.25 c1.24,0,2.25-1.01,2.25-2.25S16.99,11.5,15.75,11.5z M12.74,7H8.5v4.24l1.59-1.59l2.12,2.12l1.06-1.06l-2.12-2.12L12.74,7z"/></svg>