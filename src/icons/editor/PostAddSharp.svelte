<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g/><g><polygon points="14,15 5,15 5,6 11,6 11,5 4,5 4,16 15,16 15,9 14,9"/><polygon points="7,8 7,9 11,9 12,9 12,8"/><rect height={size} width={size} x="7" y="10"/><rect height={size} width={size} x="7" y="12"/><polygon points="15,3 14,3 14,5 12,5 12,6 14,6 14,8 15,8 15,6 17,6 17,5 15,5"/></g></g></svg>