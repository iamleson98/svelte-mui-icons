<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><circle cx="10" cy="3.75" r="1.75"/><path d="M11.5,7h-3C7.67,7,7,7.67,7,8.5V12c0,0.55,0.45,1,1,1h0.5v4c0,0.55,0.45,1,1,1h1c0.55,0,1-0.45,1-1v-4H12 c0.55,0,1-0.45,1-1V8.5C13,7.67,12.33,7,11.5,7z"/></g></g></svg>