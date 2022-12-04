<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/></g><g><path d="M9.25,8.07C7.4,8.42,6,10.05,6,12c0,2.21,1.79,4,4,4c2.21,0,4-1.79,4-4c0-1.95-1.4-3.58-3.25-3.93l0-3.2l1.19,1.19L13,5 l-3-3L7,5l1.06,1.06l1.19-1.19L9.25,8.07z M7.5,12c0-1.38,1.12-2.5,2.5-2.5c1.38,0,2.5,1.12,2.5,2.5s-1.12,2.5-2.5,2.5 C8.62,14.5,7.5,13.38,7.5,12z"/></g></svg>