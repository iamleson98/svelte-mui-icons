<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0" y="0"/><g><path d="M4,16h10v1H3V6h1V16z M17,3v11H6V3H17z M15.04,6.38l-0.71-0.71l-4.24,4.24L8.67,8.5L7.96,9.21l2.12,2.12L15.04,6.38z"/></g></g></svg>