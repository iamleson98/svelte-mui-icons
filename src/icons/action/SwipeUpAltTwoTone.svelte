<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><circle cx="10" cy="12" opacity=".3" r="2.5"/><path d="M10.75,4.87l1.19,1.19L13,5l-3-3L7,5l1.06,1.06l1.19-1.19l0,3.2C7.4,8.42,6,10.05,6,12c0,2.21,1.79,4,4,4 c2.21,0,4-1.79,4-4c0-1.95-1.4-3.58-3.25-3.93L10.75,4.87z M10,14.5c-1.38,0-2.5-1.12-2.5-2.5S8.62,9.5,10,9.5 c1.38,0,2.5,1.12,2.5,2.5S11.38,14.5,10,14.5z"/></g></svg>