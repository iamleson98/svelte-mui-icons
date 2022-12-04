<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M17,14.88V11.5h2v-3h-8.38L17,14.88z M2.93,2.93L1.87,3.99l1.66,1.66C2.02,6.51,1,8.14,1,10c0,2.76,2.24,5,5,5 c1.87,0,3.48-1.03,4.33-2.55l5.68,5.68l1.06-1.06L2.93,2.93z M6,12c-1.1,0-2-0.9-2-2c0-1.06,0.83-1.94,1.88-2L8,10.12 C7.93,11.17,7.06,12,6,12z"/></g></svg>