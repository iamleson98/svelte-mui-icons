<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 24 24" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M17,17h2v4c0,1.1-0.9,2-2,2H7c-1.1,0-2-0.9-2-2V3c0-1.1,0.9-1.99,2-1.99L17,1c1.1,0,2,0.9,2,2v4h-2V6H7v12h10V17z M22,12 l-4-4v3h-5v2h5v3L22,12z"/></svg>