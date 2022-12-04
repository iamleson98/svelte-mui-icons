<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M11.64,9.51C12.46,8.98,13,8.05,13,7c0-1.66-1.34-3-3-3C8.95,4,8.02,4.54,7.49,5.36L11.64,9.51z M15.99,13.87 c-0.07-0.62-0.41-1.18-0.95-1.5c-0.35-0.21-0.72-0.39-1.1-0.56L15.99,13.87z M2.93,2.93L1.87,3.99l7.07,7.07 c-1.44,0.15-2.78,0.62-3.97,1.31C4.36,12.72,4,13.39,4,14.09V16h9.88l2.13,2.13l1.06-1.06L2.93,2.93z"/></svg>