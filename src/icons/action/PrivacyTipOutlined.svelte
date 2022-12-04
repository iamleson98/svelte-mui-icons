<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/><path d="M10,3.6l5,2.25v3.5c0,3.18-2.22,6.32-5,7.12c-2.78-0.8-5-3.94-5-7.12v-3.5L10,3.6 M10,2.5L4,5.2v4.15 c0,3.63,2.56,7.33,6,8.15c3.44-0.82,6-4.52,6-8.15V5.2L10,2.5L10,2.5z M10.5,9h-1v4h1V9z M10.5,7h-1v1h1V7z"/></g></svg>