<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/></g><g><g><rect height={size} width={size} x="5" y="4"/><rect height={size} width="4.5" x="5" y="15"/><rect height={size} width="4.5" x="5" y="12.25"/><rect height={size} width={size} x="5" y="6.75"/><rect height={size} width={size} x="5" y="9.5"/><polygon points="12.17,14.59 11.46,13.88 10.76,14.59 12.17,16 15,13.17 14.29,12.46"/></g></g></svg>