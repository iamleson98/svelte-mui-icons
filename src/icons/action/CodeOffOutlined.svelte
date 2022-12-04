<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M18,10l-2.94,2.94L14,11.88L15.88,10l-3.94-3.94L13,5L18,10z M16.01,18.13l1.06-1.06L2.93,2.93L1.87,3.99l3.07,3.07L2,10 l5,5l1.06-1.06L4.12,10L6,8.12L16.01,18.13z"/></svg>