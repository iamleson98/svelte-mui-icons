<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M16.5,13.5h-13v-9H11V3H3.5C2.67,3,2,3.67,2,4.5v9C2,14.33,2.67,15,3.5,15H7v2h6v-2h3.5c0.83,0,1.5-0.67,1.5-1.5V11h-1.5 V13.5z"/><polygon points="14.48,11 18,7.48 16.94,6.42 15.25,8.11 15.25,3 13.75,3 13.75,8.14 12.06,6.45 11,7.52"/></g></g></svg>