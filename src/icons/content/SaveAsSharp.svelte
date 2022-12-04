<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M17,11.46V6l-3-3H3v14h8.47L17,11.46z M12.5,8.5h-7v-3h7V8.5z M12.25,12.5c0,1.24-1.01,2.25-2.25,2.25 s-2.25-1.01-2.25-2.25s1.01-2.25,2.25-2.25S12.25,11.26,12.25,12.5z M16.82,13.77l1.41,1.41L14.41,19H13l0-1.41L16.82,13.77z M17.31,13.27l0.98-0.98l1.41,1.41l-0.98,0.98L17.31,13.27z"/></g></svg>