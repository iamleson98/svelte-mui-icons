<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><polygon points="14.5,15 5.5,15 5.5,5 14.5,5 14.5,6 16,6 16,1 4,1 4,19 16,19 16,14 14.5,14"/><polygon points="17.03,7.97 17.5,9 17.97,7.97 19,7.5 17.97,7.03 17.5,6 17.03,7.03 16,7.5"/><polygon points="13,7 12.06,9.06 10,10 12.06,10.94 13,13 13.94,10.94 16,10 13.94,9.06"/><polygon points="17.5,11 17.03,12.03 16,12.5 17.03,12.97 17.5,14 17.97,12.97 19,12.5 17.97,12.03"/></g></g></svg>