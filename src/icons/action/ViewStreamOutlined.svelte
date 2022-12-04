<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M3,6.5v7C3,14.33,3.67,15,4.5,15h11c0.83,0,1.5-0.67,1.5-1.5v-7C17,5.67,16.33,5,15.5,5h-11C3.67,5,3,5.67,3,6.5z M15.5,6.5 v2.75h-11V6.5H15.5z M4.5,13.5v-2.75h11v2.75H4.5z"/></svg>