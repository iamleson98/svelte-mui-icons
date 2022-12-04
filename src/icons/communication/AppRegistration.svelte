<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><rect height={size} width={size} x="8.5" y="4"/><rect height={size} width={size} x="4" y="13"/><rect height={size} width={size} x="4" y="8.5"/><rect height={size} width={size} x="4" y="4"/><path d="M16.41,9.47l-0.88-0.88c-0.12-0.12-0.32-0.12-0.44,0l-0.66,0.66l1.31,1.31l0.66-0.66C16.53,9.78,16.53,9.59,16.41,9.47z"/><polygon points="9,14.69 9,16 10.31,16 15.31,11 14,9.69"/><polygon points="11.5,10.77 11.5,8.5 8.5,8.5 8.5,11.5 10.77,11.5"/><rect height={size} width={size} x="13" y="4"/></g></g></svg>