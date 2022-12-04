<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><g><path d="M6.12,4H18v11.88l-1.5-1.5V7H9.12L6.12,4z M16.72,18.84L13.88,16H2V4.12L1.16,3.28l1.06-1.06l15.56,15.56L16.72,18.84z M12.38,14.5L4.88,7H3.5v7.5H12.38z"/></g></svg>