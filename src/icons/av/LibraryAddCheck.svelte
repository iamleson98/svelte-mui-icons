<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0" y="0"/><g><path d="M4,16h10v1H4c-0.55,0-1-0.45-1-1V6h1V16z M17,4v9c0,0.55-0.45,1-1,1H7c-0.55,0-1-0.45-1-1V4c0-0.55,0.45-1,1-1h9 C16.55,3,17,3.45,17,4z M15.04,6.38l-0.71-0.71l-4.24,4.24L8.67,8.5L7.96,9.21l2.12,2.12L15.04,6.38z"/></g></g></svg>