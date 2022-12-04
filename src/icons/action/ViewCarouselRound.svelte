<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M2.5,6.5h2C4.78,6.5,5,6.72,5,7v6c0,0.28-0.22,0.5-0.5,0.5h-2C2.22,13.5,2,13.28,2,13V7C2,6.72,2.22,6.5,2.5,6.5z M15,7v6 c0,0.28,0.22,0.5,0.5,0.5h2c0.28,0,0.5-0.22,0.5-0.5V7c0-0.28-0.22-0.5-0.5-0.5h-2C15.22,6.5,15,6.72,15,7z M6.5,5h7 C13.78,5,14,5.22,14,5.5v9c0,0.28-0.22,0.5-0.5,0.5h-7C6.22,15,6,14.78,6,14.5v-9C6,5.22,6.22,5,6.5,5z"/></svg>