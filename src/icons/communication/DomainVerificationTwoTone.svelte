<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M5,15h10V7H5V15z M7.53,10.65l1.41,1.41l3.54-3.54l0.71,0.71l-4.24,4.24l-2.12-2.12L7.53,10.65z" opacity=".3"/><path d="M15,4H5C4.45,4,4,4.45,4,5v10c0,0.55,0.45,1,1,1h10c0.55,0,1-0.45,1-1V5C16,4.45,15.55,4,15,4z M15,15H5V7h10V15z"/><polygon points="13.18,9.23 12.47,8.53 8.94,12.06 7.53,10.65 6.82,11.35 8.94,13.47"/></g></g></svg>