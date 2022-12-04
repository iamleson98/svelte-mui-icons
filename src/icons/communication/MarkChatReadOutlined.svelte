<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/><path d="M10,14H6l-3,3V4c0-0.55,0.45-1,1-1h12c0.55,0,1,0.45,1,1v4l-1-0.02V4H4v9l6,0V14z M18,10.76l-0.71-0.71l-3.54,3.54 l-1.41-1.41l-0.71,0.71L13.76,15L18,10.76z"/></g></svg>