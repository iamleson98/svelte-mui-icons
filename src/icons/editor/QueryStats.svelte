<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M16.44,15.38C16.79,14.84,17,14.19,17,13.5c0-1.93-1.57-3.5-3.5-3.5S10,11.57,10,13.5s1.57,3.5,3.5,3.5 c0.69,0,1.34-0.21,1.88-0.56L17.94,19L19,17.94L16.44,15.38z M13.5,15.5c-1.1,0-2-0.9-2-2s0.9-2,2-2s2,0.9,2,2S14.6,15.5,13.5,15.5z M17.78,2L19,2.87l-3.88,5.9h0C14.61,8.59,14.07,8.5,13.5,8.5L17.78,2z M13.5,8.5c-0.58,0-1.13,0.1-1.65,0.28l0,0l-0.78-1.1 l-3.41,5.36l-2.48-2.97l-2.96,4.81L1,14l4-6.5l2.5,3L11,5L13.5,8.5z"/></svg>