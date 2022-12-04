<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><polygon points="13,7 7,7 7,13 8.5,13 8.5,18 11.5,18 11.5,13 13,13"/><rect height="2.83" transform="matrix(0.7071 -0.7071 0.7071 0.7071 0.1005 8.2426)" width="2.83" x="8.59" y="2.59"/></g></g></svg>