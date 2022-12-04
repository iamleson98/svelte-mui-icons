<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/></g><g><g><path d="M17,4.86L10,10L6.5,6.5L3,9V7.16l3.66-2.62l3.49,3.49L17,3L17,4.86z M17,12.5h-3.5l-3.36,2.52L5.5,10.3L3,12.14L3,14 l2.3-1.69L10,17l4-3h3V12.5z"/></g></g></svg>