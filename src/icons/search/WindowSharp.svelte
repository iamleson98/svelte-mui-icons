<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><g><rect height="6.25" width="6.25" x="3" y="3"/></g><g><rect height="6.25" width="6.25" x="10.75" y="3"/></g><g><rect height="6.25" width="6.25" x="10.75" y="10.75"/></g><g><rect height="6.25" width="6.25" x="3" y="10.75"/></g></g></g></svg>