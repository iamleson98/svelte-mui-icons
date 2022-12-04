<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M15,7.25c0.41,0,0.75-0.34,0.75-0.75V5.75h0.75c0.41,0,0.75-0.34,0.75-0.75s-0.34-0.75-0.75-0.75h-0.75V3.5 c0-0.41-0.34-0.75-0.75-0.75s-0.75,0.34-0.75,0.75v0.75H13.5c-0.41,0-0.75,0.34-0.75,0.75s0.34,0.75,0.75,0.75h0.75V6.5 C14.25,6.91,14.59,7.25,15,7.25z M15,15.52c0,0.71-0.71,1.19-1.37,0.93L10,15l-3.63,1.45C5.71,16.71,5,16.23,5,15.52V4.5 C5,3.67,5.67,3,6.5,3l5.04,0C11.19,3.59,11,4.27,11,5c0,2.21,1.79,4,4,4V15.52z"/></svg>