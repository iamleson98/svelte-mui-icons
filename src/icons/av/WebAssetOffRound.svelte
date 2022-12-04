<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><g><path d="M17.25,17.25L2.75,2.75c-0.29-0.29-0.77-0.29-1.06,0l0,0c-0.29,0.29-0.29,0.77,0,1.06L2.38,4.5C2.14,4.77,2,5.12,2,5.5v9 C2,15.33,2.67,16,3.5,16h10.38l2.31,2.31c0.29,0.29,0.77,0.29,1.06,0h0C17.54,18.02,17.54,17.54,17.25,17.25z M3.5,14.5V7h1.38 l7.5,7.5H3.5z M6.12,4H16.5C17.33,4,18,4.67,18,5.5v9c0,0.38-0.14,0.73-0.38,1l-1.12-1.12V7H9.12L6.12,4z"/></g></svg>