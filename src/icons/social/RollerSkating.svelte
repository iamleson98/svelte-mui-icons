<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M3.5,13.5V1h6.75v2.5H8C7.72,3.5,7.5,3.73,7.5,4S7.72,4.5,8,4.5h2.25v1H8C7.72,5.5,7.5,5.73,7.5,6S7.72,6.5,8,6.5h2.53 c0.19,0.27,0.46,0.47,0.79,0.57l3.4,1.03c1.06,0.32,1.78,1.3,1.78,2.4v3H3.5z M6.5,16.75c0-1.24-1.01-2.25-2.25-2.25 S2,15.51,2,16.75S3.01,19,4.25,19S6.5,17.99,6.5,16.75z M18,16.75c0-1.24-1.01-2.25-2.25-2.25s-2.25,1.01-2.25,2.25 S14.51,19,15.75,19S18,17.99,18,16.75z M12.25,16.75c0-1.24-1.01-2.25-2.25-2.25s-2.25,1.01-2.25,2.25S8.76,19,10,19 S12.25,17.99,12.25,16.75z"/></g></svg>