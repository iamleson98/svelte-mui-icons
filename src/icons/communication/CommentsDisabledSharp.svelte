<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M14.12,12H15v-1.5h-2.38l-1.25-1.25H15v-1.5H9.87L8.62,6.5H15V5H7.12l-3-3H18v13.88L14.12,12z M2.22,2.22L1.16,3.28L2,4.12 V15h10.88l3.84,3.84l1.06-1.06L2.22,2.22z M5,9.25v-1.5h0.63l1.5,1.5H5z M8,12v-1.5h0.38l1.5,1.5H8z"/></svg>