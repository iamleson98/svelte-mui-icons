<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M13.79,5L13,5V2.5H7V5L6.21,5C3.6,5,1.27,6.91,1.02,9.51C0.74,12.49,3.08,15,6,15v2h1.5v-2h5v2H14v-2 c2.92,0,5.26-2.51,4.98-5.49C18.73,6.91,16.4,5,13.79,5z M8.5,4h3v1h-3V4z"/></g></svg>