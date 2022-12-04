<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M10,2c-4.42,0-8,3.58-8,8s3.58,8,8,8s8-3.58,8-8S14.42,2,10,2z M6,6h5.5v1.5H6V6z M6,8.5h5.5V10H6V8.5z M8.5,12.5H6V11h2.5 V12.5z M11.76,15l-2.12-2.12l1.06-1.06l1.06,1.06l2.47-2.47l1.06,1.06L11.76,15z"/></svg>