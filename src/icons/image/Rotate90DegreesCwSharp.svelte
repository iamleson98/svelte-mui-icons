<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><g><path d="M9,11l5,5l5-5l-5-5L9,11z"/><path d="M2,11c0,3.87,3.13,7,7,7c1.43,0,2.76-0.43,3.86-1.17l-1.09-1.09C10.96,16.22,10.01,16.5,9,16.5c-3.03,0-5.5-2.47-5.5-5.5 S5.97,5.5,9,5.5v2.25l3-3l-3-3V4C5.13,4,2,7.13,2,11z"/></g></g></g></svg>