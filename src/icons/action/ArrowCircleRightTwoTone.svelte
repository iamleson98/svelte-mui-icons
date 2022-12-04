<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M16.5,10c0-3.58-2.92-6.5-6.5-6.5S3.5,6.42,3.5,10s2.92,6.5,6.5,6.5S16.5,13.58,16.5,10z M10,10.75H7v-1.5 h3V7l3,3l-3,3V10.75z" opacity=".3"/><path d="M10,7l3,3l-3,3v-2.25H7v-1.5h3V7z M18,10c0-4.42-3.58-8-8-8s-8,3.58-8,8s3.58,8,8,8S18,14.42,18,10z M3.5,10 c0-3.58,2.92-6.5,6.5-6.5s6.5,2.92,6.5,6.5s-2.92,6.5-6.5,6.5S3.5,13.58,3.5,10z"/></g></g></svg>