<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/><path d="M13,14.5L13,14.5c0,0.28-0.22,0.5-0.5,0.5h-5C7.22,15,7,14.78,7,14.5v0C7,14.22,7.22,14,7.5,14h5 C12.78,14,13,14.22,13,14.5z M9.5,12.5c0,0.28,0.22,0.5,0.5,0.5s0.5-0.22,0.5-0.5V8H13l-3-3L7,8h2.5V12.5z"/></g></svg>