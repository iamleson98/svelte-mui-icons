<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M10,3C6.52,3,3.34,4.23,0.84,6.27c-0.46,0.38-0.51,1.07-0.08,1.5l8.54,8.53c0.39,0.39,1.02,0.39,1.41,0l8.54-8.53 c0.42-0.42,0.38-1.12-0.08-1.5C16.66,4.23,13.48,3,10,3z M6.36,11.25L2.21,7.1C4.46,5.41,7.17,4.5,10,4.5 c2.83,0,5.54,0.91,7.79,2.6l-4.15,4.15C12.58,10.43,11.33,10,10,10C8.67,10,7.42,10.43,6.36,11.25z"/></g></svg>