<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 24 24" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M21,7h-1V6.5C20,6.22,19.78,6,19.5,6h-1C18.22,6,18,6.22,18,6.5V7h-1c-0.55,0-1,0.45-1,1v9c0,0.55,0.45,1,1,1h4 c0.55,0,1-0.45,1-1V8C22,7.45,21.55,7,21,7z"/><path d="M8,6c-3.31,0-6,2.69-6,6v4c0,1.1,0.9,2,2,2s2-0.9,2-2v-1c0-1.1-0.9-2-2-2H3.5v-1c0-2.48,2.02-4.5,4.5-4.5 s4.5,2.02,4.5,4.5v1H12c-1.1,0-2,0.9-2,2v1c0,1.1,0.9,2,2,2s2-0.9,2-2v-4C14,8.69,11.31,6,8,6z"/></g></g></svg>