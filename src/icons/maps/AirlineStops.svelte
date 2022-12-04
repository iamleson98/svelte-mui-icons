<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M9.25,14C9.25,10.41,6,7.5,2,7.5V6c3.56,0,6.64,1.96,8,4.76c0.72-1.49,1.96-2.87,3.68-4.08L11.5,4.5H17V10l-2.24-2.24 c-1.78,1.21-4.01,3.28-4.01,6.24h1.5v1.5h-4.5V14H9.25z"/></svg>