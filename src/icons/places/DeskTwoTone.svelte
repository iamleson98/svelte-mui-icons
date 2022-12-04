<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><rect height={size} opacity=".3" width={size} x="13.5" y="6.5"/><rect height={size} opacity=".3" width={size} x="13.5" y="10"/><path d="M2,5v10h1.5V6.5H12V15h1.5v-1.5h3V15H18V5H2z M16.5,12h-3v-2h3V12z M16.5,8.5h-3v-2h3V8.5z"/></g></g></svg>