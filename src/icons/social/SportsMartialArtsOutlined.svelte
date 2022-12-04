<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/></g><g><g><circle cx="4.5" cy="4.5" r="1.5"/><polygon points="16.79,2 9.96,7.54 8.27,6.22 11.01,4.64 7.37,1 6.67,1.71 9.38,4.42 4.25,7.38 3.31,10.78 5.13,14 6,13.51 4.39,10.65 4.88,8.87 8.5,11 9,18 10,18 10.5,10 17.5,2.71"/></g></g></svg>