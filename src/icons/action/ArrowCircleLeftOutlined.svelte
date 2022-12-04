<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/></g><g><path d="M10,13l-3-3l3-3l1.06,1.06L9.87,9.25H13v1.5H9.87l1.19,1.19L10,13z M2,10c0,4.42,3.58,8,8,8s8-3.58,8-8s-3.58-8-8-8 S2,5.58,2,10z M16.5,10c0,3.58-2.92,6.5-6.5,6.5S3.5,13.58,3.5,10S6.42,3.5,10,3.5S16.5,6.42,16.5,10z"/></g></svg>