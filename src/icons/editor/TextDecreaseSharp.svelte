<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M18,9.25v1.5h-6v-1.5H18z M4.49,12.44h4.04L9.42,15h1.73L7.39,5H5.61L1.85,15h1.73L4.49,12.44z M6.07,8.02l0.39-1.16h0.08 l0.39,1.16l1.06,2.98H5.01L6.07,8.02z"/></svg>