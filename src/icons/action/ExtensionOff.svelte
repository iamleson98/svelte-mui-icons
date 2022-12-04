<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M16.01,18.13L14.88,17H12c0-1.1-0.9-2-2-2s-2,0.9-2,2H4.5C3.67,17,3,16.33,3,15.5V12c1.1,0,2-0.9,2-2S4.1,8,3,8V5.12 L1.87,3.99l1.06-1.06l0.51,0.51l13.63,13.63L16.01,18.13z M17,8V4.5C17,3.67,16.33,3,15.5,3H12c0-1.1-0.9-2-2-2S8,1.9,8,3H5.12 L17,14.88V12c1.1,0,2-0.9,2-2S18.1,8,17,8z"/></svg>