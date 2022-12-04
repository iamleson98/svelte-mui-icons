<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><rect height={size} width="1.5" x="4" y="4"/><rect height="6.5" width="1.5" x="14.5" y="4"/><rect height={size} width="1.5" x="9.25" y="8.5"/><rect height={size} width="1.5" x="9.25" y="4"/><rect height={size} width="1.5" x="9.25" y="13"/><polygon points="18,13.56 16.94,12.5 15.25,14.19 13.56,12.5 12.5,13.56 14.19,15.25 12.5,16.94 13.56,18 15.25,16.31 16.94,18 18,16.94 16.31,15.25"/></g></g></svg>