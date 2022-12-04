<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><g><polygon fill-rule="evenodd" points="5.22,9 6,16 14,16 14.78,9"/></g><g><polygon fill-rule="evenodd" points="16.3,6 15.14,7.14 12,4 8,4 4.86,7.14 3.7,6 3,6.71 4.31,8 15.69,8 17,6.71"/></g></g></g></svg>