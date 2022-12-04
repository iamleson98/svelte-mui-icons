<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/><path d="M3,4v12h7.1c-0.07-0.32-0.1-0.66-0.1-1c0-2.76,2.24-5,5-5c0.71,0,1.39,0.15,2,0.42V4H3z M16,6.18L10,10L4,6.18V5l6,3.82 L16,5V6.18z M13.76,17l-2.12-2.12l0.71-0.71l1.41,1.41l3.54-3.54L18,12.76L13.76,17z"/></g></svg>