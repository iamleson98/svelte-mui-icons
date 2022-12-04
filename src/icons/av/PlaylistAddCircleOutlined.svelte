<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M10,2c-4.42,0-8,3.58-8,8s3.58,8,8,8s8-3.58,8-8S14.42,2,10,2z M10,16.5c-3.58,0-6.5-2.92-6.5-6.5S6.42,3.5,10,3.5 s6.5,2.92,6.5,6.5S13.58,16.5,10,16.5z M8.5,11H6v1.5h2.5V11z M11.5,6H6v1.5h5.5V6z M11.5,8.5H6V10h5.5V8.5z M15.5,11v1.5H14V14 h-1.5v-1.5H11V11h1.5V9.5H14V11H15.5z"/></svg>