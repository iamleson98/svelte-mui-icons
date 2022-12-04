<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M8,16H6.5l0-7c0-0.83,0.67-1.5,1.5-1.5l6.13,0l-1.19-1.19L14,5.25l3,3l-3,3l-1.06-1.06L14.13,9L8,9V16z"/></g></svg>