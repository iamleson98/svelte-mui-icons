<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><g><rect fill={color} height={size} width={size}/></g></g><g><g><polygon points="2,18 15,18 15,7.5 18,7.5 18,2"/><rect height="1.5" width="1.5" x="16.5" y="16.5"/><rect height="6.05" width="1.5" x="16.5" y="9"/></g></g></svg>