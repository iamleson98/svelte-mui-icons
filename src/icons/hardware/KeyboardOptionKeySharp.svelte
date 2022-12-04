<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><polygon points="8,5 3,5 3,6.5 7.13,6.5 12.04,15 17,15 17,13.5 12.91,13.5"/><rect height="1.5" width={size} x="12" y="5"/></g></g></svg>