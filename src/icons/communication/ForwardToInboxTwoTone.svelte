<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/><path d="M15,12.5l3,3l-3,3V16h-3v-1h3V12.5z M11,15H4V6.18L10,10l6-3.82V12h1V5c0-0.55-0.45-1-1-1H4C3.45,4,3,4.45,3,5v10 c0,0.55,0.45,1,1,1h7L11,15z M16,5l-6,3.82L4,5H16z"/><path d="M11,15H4V6.18L10,10l6-3.82V12l-2,0C12.34,12,11,13.34,11,15L11,15z M16,5l-6,3.82L4,5H16z" opacity=".3"/></g></svg>