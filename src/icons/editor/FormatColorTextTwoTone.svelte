<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><rect height={size} width={size} x="2" y="16"/><path d="M7.99,10.44h4.04L12.92,13h1.73L10.89,3H9.11L5.35,13h1.73L7.99,10.44z M9.57,6.02l0.39-1.16h0.08l0.39,1.16l1.06,2.98 H8.51L9.57,6.02z"/></g></g></svg>