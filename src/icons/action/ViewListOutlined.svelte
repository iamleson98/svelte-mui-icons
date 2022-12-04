<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M3,5v10h14V5H3z M15.5,7.83h-8V6.5h8V7.83z M7.5,9.33h8v1.33h-8V9.33z M6,10.67H4.5V9.33H6V10.67z M6,6.5v1.33H4.5V6.5H6z M4.5,12.17H6v1.33H4.5V12.17z M7.5,13.5v-1.33h8v1.33H7.5z"/></svg>