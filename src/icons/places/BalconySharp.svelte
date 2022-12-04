<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M8.5,8.5V10H7V8.5H8.5z M13,10V8.5h-1.5V10H13z M17,12v6H3v-6h1V8c0-3.31,2.69-6,6-6s6,2.69,6,6v4H17z M6.12,13.5H4.5v3 h1.62V13.5z M9.25,13.5H7.62v3h1.62V13.5z M9.25,12l0-8.44C7.12,3.92,5.5,5.77,5.5,8v4H9.25z M10.75,12h3.75V8 c0-2.23-1.62-4.08-3.75-4.44V12z M12.38,13.5h-1.62v3h1.62V13.5z M15.5,13.5h-1.62v3h1.62V13.5z"/></svg>