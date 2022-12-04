<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M11.75,16C11.34,16,11,15.66,11,15.25v-4.69l-4-4L7,7.5c0,0.41-0.34,0.75-0.75,0.75C5.84,8.25,5.5,7.91,5.5,7.5l0-2.5 c0-0.55,0.45-1,1-1L9,4c0.41,0,0.75,0.34,0.75,0.75C9.75,5.16,9.41,5.5,9,5.5l-0.94,0l4,4c0.28,0.28,0.44,0.66,0.44,1.06v4.69 C12.5,15.66,12.16,16,11.75,16z"/></g></svg>