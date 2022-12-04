<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><polygon points="14,14 18,10 14,6 12.94,7.06 15.13,9.25 8,9.25 8,10.75 15.13,10.75 12.94,12.94"/><path d="M15.5,15.5h-11v-11h11V6H17V4.5C17,3.67,16.33,3,15.5,3h-11C3.67,3,3,3.67,3,4.5v11C3,16.33,3.67,17,4.5,17h11 c0.83,0,1.5-0.67,1.5-1.5V14h-1.5V15.5z"/></g></g></svg>