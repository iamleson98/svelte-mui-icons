<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><g><rect fill={color} height={size} width={size}/></g></g><g><g><rect height="1.5" width="1.5" x="16.5" y="16.5"/><rect height="6.05" width="1.5" x="16.5" y="9"/><path d="M10,3C6.12,3,2.6,4.53,0,7.01L10,17l5-5V7.5h4.51L20,7.01C17.4,4.53,13.88,3,10,3z"/></g></g></svg>