<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M15.25,12.13V3h-6v12.5h-3V7.87C7.26,7.55,8,6.62,8,5.5C8,4.12,6.88,3,5.5,3S3,4.12,3,5.5c0,1.12,0.74,2.05,1.75,2.37V17 h6V4.5h3v7.63C12.74,12.45,12,13.38,12,14.5c0,1.38,1.12,2.5,2.5,2.5s2.5-1.12,2.5-2.5C17,13.38,16.26,12.45,15.25,12.13z"/></g></g></svg>