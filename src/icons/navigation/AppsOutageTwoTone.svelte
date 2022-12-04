<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M7,7H4V4h3V7z M7,8.5H4v3h3V8.5z M11.5,8.5h-3v3h3V8.5z M7,13H4v3h3V13z M11.5,13h-3v3h3V13z M16,13h-3v3h3V13z M20,4 c0,2.21-1.79,4-4,4s-4-1.79-4-4s1.79-4,4-4S20,1.79,20,4z M16.5,5h-1v1h1V5z M16.5,2h-1v2h1V2z M16,9.5v2h-3V8.61 C13.86,9.17,14.89,9.5,16,9.5z M11.39,7H8.5V4h2C10.5,5.11,10.83,6.14,11.39,7z"/></svg>