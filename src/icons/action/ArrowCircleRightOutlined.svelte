<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/></g><g><path d="M10,7l3,3l-3,3l-1.06-1.06l1.19-1.19H7v-1.5h3.13L8.94,8.06L10,7z M18,10c0-4.42-3.58-8-8-8s-8,3.58-8,8s3.58,8,8,8 S18,14.42,18,10z M3.5,10c0-3.58,2.92-6.5,6.5-6.5s6.5,2.92,6.5,6.5s-2.92,6.5-6.5,6.5S3.5,13.58,3.5,10z"/></g></svg>