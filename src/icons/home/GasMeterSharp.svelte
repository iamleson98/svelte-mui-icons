<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M16,3.5h-3.5V2H11v1.5H9V2H7.5v1.5H4V18h12V3.5z M10,14.5c-1.1,0-2-0.88-2-1.97c0-0.87,0.35-1.11,2-3.03 c1.64,1.91,2,2.16,2,3.03C12,13.62,11.1,14.5,10,14.5z M13,8H7V6.5h6V8z"/></g></svg>