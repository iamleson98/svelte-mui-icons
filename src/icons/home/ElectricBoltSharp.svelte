<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><polygon points="12.25,1.75 2.25,11 10.8,11.5 6.75,17.25 7.75,18.25 17.75,9 9.2,8.5 13.25,2.75"/></g></g></svg>