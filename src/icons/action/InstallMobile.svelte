<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M14.5,15h-9V5H12V1H5.5C4.67,1,4,1.67,4,2.5v15C4,18.33,4.67,19,5.5,19h9c0.83,0,1.5-0.67,1.5-1.5V13h-1.5V15z"/><polygon points="15.23,11 18.75,7.48 17.69,6.42 16,8.11 16,3 14.5,3 14.5,8.14 12.81,6.45 11.75,7.52"/></g></g></svg>