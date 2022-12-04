<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0" y="0"/><path d="M10,2.5L4,5.2v4.15c0,3.63,2.56,7.33,6,8.15c3.44-0.82,6-4.52,6-8.15V5.2L10,2.5z M10.5,13h-1V9h1V13z M10.5,8h-1V7h1V8z"/></g></svg>