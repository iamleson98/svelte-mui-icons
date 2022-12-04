<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><g><path d="M15,11.03C13.52,10.3,12.5,8.77,12.5,7c0-0.73,0.17-1.41,0.48-2.02C12.4,4.56,11.73,4.25,11,4.1V2H9v2.1 C6.72,4.56,5,6.58,5,9v5H4v1.5h12V14h-1L15,11.03z M10,18c0.83,0,1.5-0.67,1.5-1.5h-3C8.5,17.33,9.17,18,10,18z M20,6.31h-2.25V4 h-1.5v2.31H14v1.38h2.25V10h1.5V7.69H20V6.31z"/></g></svg>