<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/><path d="M15,16H5v-6h10V16z M15,9h-3.5V8h-3v1H5V4h10V9z" opacity=".3"/><path d="M15,3H5C4.45,3,4,3.45,4,4v12c0,0.55,0.45,1,1,1h10c0.55,0,1-0.45,1-1V4C16,3.45,15.55,3,15,3z M15,16H5v-6h10V16z M15,9 h-3.5V8h-3v1H5V4h10V9z"/></g></svg>