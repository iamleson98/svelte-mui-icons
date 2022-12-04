<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M6.75,3c2.37,0,4.33,1.73,4.69,4l3.69,0l-1.19-1.19L15,4.75l3,3l-3,3l-1.06-1.06l1.19-1.19L10,8.46c0,0,0-0.12,0-0.71 C10,5.96,8.54,4.5,6.75,4.5S3.5,5.96,3.5,7.75S4.96,11,6.75,11H7.5v6H6v-4.56l0,0c-2.27-0.36-4-2.32-4-4.69C2,5.13,4.13,3,6.75,3"/></g></svg>