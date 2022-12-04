<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M15.5,7h-11C3.67,7,3,7.67,3,8.5v3C3,12.33,3.67,13,4.5,13h11c0.83,0,1.5-0.67,1.5-1.5v-3C17,7.67,16.33,7,15.5,7z M15.5,11.5h-11v-3h11V11.5z"/></g></svg>