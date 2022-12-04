<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 24 24" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><polygon points="12.03,6.3 11.97,6.3 10.95,9.19 13.05,9.19"/><rect height={size} width={size} x="3" y="17"/><path d="M12,15c3.31,0,6-2.69,6-6s-2.69-6-6-6S6,5.69,6,9S8.69,15,12,15z M11.37,5h1.25l2.63,7h-1.21l-0.63-1.79h-2.83L9.96,12 H8.74L11.37,5z"/><rect height={size} width={size} x="7" y="17"/><rect height={size} width={size} x="11" y="17"/><rect height={size} width={size} x="15" y="17"/></g></g></svg>