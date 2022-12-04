<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M2.53,14.12c-0.29-0.29-0.29-0.77,0-1.06L6.08,9.5c0.98-0.98,2.56-0.98,3.54,0l0.71,0.71c0.39,0.39,1.02,0.39,1.41,0 l3.23-3.23l-1.12-1.12C13.54,5.54,13.76,5,14.21,5h3.29C17.78,5,18,5.22,18,5.5v3.29c0,0.45-0.54,0.67-0.85,0.35l-1.12-1.12 l-3.23,3.23c-0.98,0.98-2.56,0.98-3.54,0l-0.7-0.7c-0.39-0.39-1.02-0.39-1.41,0l-3.56,3.56C3.3,14.41,2.82,14.41,2.53,14.12z"/></svg>