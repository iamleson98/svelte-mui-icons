<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><polygon points="16,12 16,9.75 14,9.75 14,9 15,9 15,9.25 16,9.25 16,8 13,8 13,10.25 15,10.25 15,11 14,11 14,10.75 13,10.75 13,10.88 14.12,12"/><polygon points="2.93,2.93 1.87,3.99 6,8.12 6,9.5 5,9.5 5,8 4,8 4,12 5,12 5,10.5 6,10.5 6,12 7,12 7,9.12 9,11.12 9,12 9.88,12 16.01,18.13 17.07,17.07"/></g></g></svg>