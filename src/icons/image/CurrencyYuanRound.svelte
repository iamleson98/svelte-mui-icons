<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M5.88,3C5.28,3,4.93,3.66,5.25,4.16L9.03,10l-2.75,0c-0.41,0-0.77,0.32-0.78,0.73c-0.01,0.42,0.33,0.77,0.75,0.77h3v4.72 c0,0.41,0.32,0.77,0.73,0.78c0.42,0.01,0.77-0.33,0.77-0.75V11.5h2.97c0.41,0,0.77-0.32,0.78-0.73c0.01-0.42-0.33-0.77-0.75-0.77 l-2.78,0l3.78-5.84C15.07,3.66,14.72,3,14.12,3c-0.25,0-0.49,0.13-0.63,0.34L10,8.74l-3.49-5.4C6.37,3.13,6.13,3,5.88,3z"/></g></svg>