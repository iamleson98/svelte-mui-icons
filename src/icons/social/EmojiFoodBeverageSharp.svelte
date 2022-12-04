<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g/><g><path d="M15,5H7.75v2.17L9,8v3H6V8l1.25-0.83V5H5v9h9V9h1c0.55,0,1-0.45,1-1V6C16,5.45,15.55,5,15,5z M15,8h-1V6h1V8z"/><rect height={size} width={size} x="4" y="15"/></g></g></svg>