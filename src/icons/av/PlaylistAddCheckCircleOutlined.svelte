<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M14.24,10.4l1.06,1.06L11.76,15l-2.12-2.12l1.06-1.06l1.06,1.06L14.24,10.4z M3.5,10c0,3.58,2.92,6.5,6.5,6.5 s6.5-2.92,6.5-6.5S13.58,3.5,10,3.5S3.5,6.42,3.5,10z M18,10c0,4.42-3.58,8-8,8s-8-3.58-8-8s3.58-8,8-8S18,5.58,18,10z M8.5,11H6 v1.5h2.5V11z M11.5,6H6v1.5h5.5V6z M11.5,8.5H6V10h5.5V8.5z"/></svg>