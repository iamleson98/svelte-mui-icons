<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M17,5h-2V1H5v4H3v13h14V5z M6.5,2.5h7V5h-7V2.5z M10,15.5c-2.21,0-4-1.79-4-4c0-2.21,1.79-4,4-4s4,1.79,4,4 C14,13.71,12.21,15.5,10,15.5z"/><polygon points="10.5,9.5 9.5,9.5 9.5,11.71 11.15,13.35 11.85,12.65 10.5,11.29"/></g></g></svg>