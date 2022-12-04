<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M6,8h1v4H6v-1.5H5V12H4V8h1v1.5h1V8z M13.5,12h2c0.28,0,0.5-0.22,0.5-0.5v-1.25c0-0.28-0.22-0.5-0.5-0.5H14V9h1v0.25h1V8.5 C16,8.22,15.78,8,15.5,8h-2C13.22,8,13,8.22,13,8.5v1.25c0,0.28,0.22,0.5,0.5,0.5H15V11h-1v-0.25h-1v0.75 C13,11.78,13.22,12,13.5,12z M11.5,11H10V8H9v4l2.5,0V11z"/></g></svg>