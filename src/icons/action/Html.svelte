<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M4,8h1v4H4v-1.5H3V12H2V8h1v1.5h1V8z M6,9h1v3h1V9h1V8H6V9z M18.5,11H17V8h-1v4l2.5,0V11z M14.5,8h-4 C10.22,8,10,8.22,10,8.5V12h1V9h1v2h1V9h1v3h1V8.5C15,8.22,14.78,8,14.5,8z"/></g></svg>