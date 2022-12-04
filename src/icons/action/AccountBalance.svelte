<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 24 24" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><rect height={size} width={size} x="4" y="10"/><rect height={size} width={size} x="10.5" y="10"/><rect height={size} width={size} x="2" y="19"/><rect height={size} width={size} x="17" y="10"/><polygon points="12,1 2,6 2,8 22,8 22,6"/></g></g></svg>