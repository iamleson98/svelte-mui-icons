<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M16.5,13.5V8.64l-5.18-1.57c-0.33-0.1-0.6-0.3-0.79-0.57H7.5v-1h2.75v-1H7.5v-1h2.75V1H3.5v12.5H16.5z M6.5,16.75 c0-1.24-1.01-2.25-2.25-2.25S2,15.51,2,16.75S3.01,19,4.25,19S6.5,17.99,6.5,16.75z M18,16.75c0-1.24-1.01-2.25-2.25-2.25 s-2.25,1.01-2.25,2.25S14.51,19,15.75,19S18,17.99,18,16.75z M12.25,16.75c0-1.24-1.01-2.25-2.25-2.25s-2.25,1.01-2.25,2.25 S8.76,19,10,19S12.25,17.99,12.25,16.75z"/></g></svg>