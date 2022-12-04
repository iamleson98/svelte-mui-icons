<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M17.56,8.06l-2.12-2.12c-0.28-0.28-0.66-0.44-1.06-0.44H7.5V4.75C7.5,4.34,7.16,4,6.75,4S6,4.34,6,4.75V5.5H5.62 c-0.4,0-0.78,0.16-1.06,0.44L2.44,8.06C2.16,8.34,2,8.72,2,9.12v4.38C2,14.33,2.67,15,3.5,15h8H13h3.5c0.83,0,1.5-0.67,1.5-1.5V9.12 C18,8.72,17.84,8.34,17.56,8.06z M3.5,13.5V10h8v3.5H3.5z M16.5,13.5H13V9.12l1.75-1.75l1.75,1.75V13.5z"/></svg>