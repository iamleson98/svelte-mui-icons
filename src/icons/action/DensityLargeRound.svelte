<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M3.75,4.5h12.5C16.66,4.5,17,4.16,17,3.75C17,3.34,16.66,3,16.25,3H3.75C3.34,3,3,3.34,3,3.75C3,4.16,3.34,4.5,3.75,4.5z"/><path d="M16.25,15.5H3.75C3.34,15.5,3,15.84,3,16.25C3,16.66,3.34,17,3.75,17h12.5c0.41,0,0.75-0.34,0.75-0.75 C17,15.84,16.66,15.5,16.25,15.5z"/></g></g></svg>