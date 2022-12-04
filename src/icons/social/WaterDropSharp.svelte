<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M10,2c0,0-6.5,5.16-6.5,9.5c0,3.59,2.91,6.5,6.5,6.5s6.5-2.91,6.5-6.5C16.5,7.16,10,2,10,2z M11,15.37 c-0.32,0.08-0.65,0.13-1,0.13c-2.21,0-4-1.79-4-4h1c0,1.65,1.35,3,3,3c0.35,0,0.69-0.06,1-0.17L11,15.37z"/></svg>