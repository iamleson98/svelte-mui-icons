<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M15.5,6h-11C3.67,6,3,6.67,3,7.5v5C3,13.33,3.67,14,4.5,14h11c0.83,0,1.5-0.67,1.5-1.5v-5C17,6.67,16.33,6,15.5,6z M15.5,12.5h-11v-5h11V12.5z"/></g></svg>