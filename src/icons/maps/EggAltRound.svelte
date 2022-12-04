<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M15.6,7.6C14,6,13.19,2,8.38,2C4.36,2,1.95,5.2,2,9.62S5.97,16,8.38,16c1.61,0,1.61,2,4.82,2C15.6,18,18,15.6,18,12.42 C18,10,17.21,9.2,15.6,7.6z M10,12.5c-1.38,0-2.5-1.12-2.5-2.5c0-1.38,1.12-2.5,2.5-2.5s2.5,1.12,2.5,2.5 C12.5,11.38,11.38,12.5,10,12.5z"/></g></g></svg>