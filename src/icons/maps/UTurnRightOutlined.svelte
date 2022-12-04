<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/></g><g><path d="M14.5,7.5C14.5,5.01,12.49,3,10,3S5.5,5.01,5.5,7.5V16H7l0-8.5c0-1.66,1.34-3,3-3s3,1.34,3,3l0,2.63l-1.19-1.19L10.75,10 l3,3l3-3l-1.06-1.06l-1.19,1.19L14.5,7.5z"/></g></svg>