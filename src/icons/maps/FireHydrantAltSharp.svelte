<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><circle cx="10" cy="11.5" r="1.25"/><path d="M17,9h-2V7h1V5.5h-1.25C14.11,3.48,12.24,2,10,2S5.89,3.48,5.25,5.5H4V7h1v2H3v5h2v2.5H4V18h12v-1.5h-1V14h2V9z M10.54,14.2c-1.94,0.37-3.6-1.3-3.24-3.24c0.2-1.08,1.08-1.96,2.16-2.16c1.94-0.37,3.6,1.3,3.24,3.24 C12.49,13.11,11.61,13.99,10.54,14.2z"/></g></g></svg>