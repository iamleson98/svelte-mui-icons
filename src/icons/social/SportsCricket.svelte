<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><circle cx="14.5" cy="5.5" r="2.5"/><path d="M12.34,11.51L5.97,5.15c-0.2-0.2-0.51-0.2-0.71,0L3.15,7.26c-0.2,0.2-0.2,0.51,0,0.71l6.36,6.36c0.2,0.2,0.51,0.2,0.71,0 l2.12-2.12C12.53,12.02,12.53,11.71,12.34,11.51z"/><rect height={size} transform="matrix(0.7071 -0.7071 0.7071 0.7071 -6.9645 13.9853)" width={size} x="12.9" y="13.4"/></g></g></svg>