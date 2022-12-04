<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M12.66,9H11V4.25C11,3.56,10.44,3,9.75,3h0C9.06,3,8.5,3.56,8.5,4.25V13l-3-1l-1,1l4,4h7.16l1-6L12.66,9z"/></g></svg>