<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/></g><g><path d="M16,15.5V3H4v12.5H2V17h6.75c0,0.69,0.56,1.25,1.25,1.25s1.25-0.56,1.25-1.25H18v-1.5H16z M9.25,15.5H5.5V14h3.75V15.5z M14.5,15.5h-3.75V14h3.75V15.5z M14.5,12.5h-9v-8h9V12.5z"/></g></svg>