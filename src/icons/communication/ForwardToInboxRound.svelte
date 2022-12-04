<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/><path d="M15,12.5l3,3l-3,3V16h-2.5c-0.28,0-0.5-0.22-0.5-0.5v0c0-0.28,0.22-0.5,0.5-0.5H15V12.5z M11,16H4c-0.55,0-1-0.45-1-1V5 c0-0.55,0.45-1,1-1h12c0.55,0,1,0.45,1,1v7h-1V6.18l-5.46,3.48c-0.33,0.21-0.75,0.21-1.07,0L4,6.18V15h7L11,16z M4,5l6,3.82L16,5H4 z"/></g></svg>