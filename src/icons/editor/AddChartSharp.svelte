<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 24 24" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><polygon points="19,19 5,19 5,5 14,5 14,3 3,3 3,21 21,21 21,10 19,10"/><rect height={size} width={size} x="11" y="7"/><rect height={size} width={size} x="15" y="13"/><rect height={size} width={size} x="7" y="10"/><polygon points="19,5 19,3 17,3 17,5 15,5 15,7 17,7 17,9 19,9 19,7 21,7 21,5"/></g></g></svg>