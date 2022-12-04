<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><g><path d="M17.07,17.07L2.93,2.93L1.87,3.99L3,5.12V15.5C3,16.33,3.67,17,4.5,17h10.38l1.13,1.13L17.07,17.07z M7,15.5H4.5V6.62 L6,8.12v3.38C6,11.78,6.22,12,6.5,12H7V15.5z M8,15.5V12h0.5C8.78,12,9,11.78,9,11.5v-0.38l3,3v1.38H8z M5.12,3H15.5 C16.33,3,17,3.67,17,4.5v10.38l-1.5-1.5V4.5H14v7c0,0.11-0.04,0.2-0.1,0.28L11,8.88V4.5H9v2.38L5.12,3z"/></g></svg>