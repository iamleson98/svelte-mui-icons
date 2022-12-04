<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M13.31,1.01L9.72,1.47C7.02,1.79,5,4.06,5,6.75c0,2.69,2.02,4.96,4.72,5.28l1.37,0.17l-0.57,0.85 C10.35,13.03,10.18,13,10,13c-2.21,0-4,1.79-4,4v1.5C6,18.78,6.22,19,6.5,19h7c0.28,0,0.5-0.22,0.5-0.5V17 c0-1.48-0.81-2.76-2.01-3.45l0.76-1.13l0.56,0.07c0.9,0.11,1.69-0.58,1.69-1.48V2.49C15,1.59,14.21,0.9,13.31,1.01z"/></g></g></svg>