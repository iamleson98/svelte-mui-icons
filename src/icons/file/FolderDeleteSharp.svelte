<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M18,6h-8L8,4H2v12h16V6z M15.5,10H15v3.5h-3.5V10H11V9h1.5V8.5H14V9h1.5V10z M14,12.5h-1.5V10H14V12.5z"/></g></svg>