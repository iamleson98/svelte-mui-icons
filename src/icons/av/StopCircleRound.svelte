<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M10,3c-3.87,0-7,3.13-7,7c0,3.87,3.13,7,7,7s7-3.13,7-7C17,6.13,13.87,3,10,3z M13,12.5c0,0.28-0.22,0.5-0.5,0.5h-5 C7.22,13,7,12.78,7,12.5v-5C7,7.22,7.22,7,7.5,7h5C12.78,7,13,7.22,13,7.5V12.5z"/></svg>