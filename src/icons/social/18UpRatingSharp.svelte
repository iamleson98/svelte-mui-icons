<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><rect height=".75" width={size} x="11" y="10.25"/><rect height=".75" width={size} x="11" y="9"/><path d="M17,3H3v14h14V3z M9,12H8V9H7V8h2V12z M13,11.5c0,0.28-0.22,0.5-0.5,0.5h-2c-0.28,0-0.5-0.22-0.5-0.5v-3 C10,8.22,10.22,8,10.5,8h2C12.78,8,13,8.22,13,8.5V11.5z"/></g></g></svg>