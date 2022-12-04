<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M11.5,7h-3C7.67,7,7,7.67,7,8.5v4C7,12.78,7.22,13,7.5,13h1v4.5C8.5,17.78,8.72,18,9,18h2c0.28,0,0.5-0.22,0.5-0.5V13h1 c0.28,0,0.5-0.22,0.5-0.5v-4C13,7.67,12.33,7,11.5,7z"/><path d="M11.65,3.65l-1.29-1.29c-0.2-0.2-0.51-0.2-0.71,0L8.35,3.65c-0.2,0.2-0.2,0.51,0,0.71l1.29,1.29c0.2,0.2,0.51,0.2,0.71,0 l1.29-1.29C11.84,4.16,11.84,3.84,11.65,3.65z"/></g></g></svg>