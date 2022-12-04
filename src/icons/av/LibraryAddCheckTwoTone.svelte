<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0" y="0"/><g><g opacity=".3"><path d="M7,4v9h9V4H7z M10.09,11.33L7.96,9.21L8.67,8.5l1.41,1.41l4.24-4.24l0.71,0.71L10.09,11.33z"/></g><g><path d="M4,16h10v1H4c-0.55,0-1-0.45-1-1V6h1V16z M17,4v9c0,0.55-0.45,1-1,1H7c-0.55,0-1-0.45-1-1V4c0-0.55,0.45-1,1-1h9 C16.55,3,17,3.45,17,4z M16,4H7v9h9V4z M8.67,8.5L7.96,9.21l2.12,2.12l4.95-4.95l-0.71-0.71l-4.24,4.24L8.67,8.5z"/></g></g></g></svg>