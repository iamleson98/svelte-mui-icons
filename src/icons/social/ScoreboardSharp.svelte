<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M14,11h-1V9h1V11z M18,4h-4V2.5h-1.5V4h-5V2.5H6V4H2v12h16V4z M8,10.5H6V11h2v1H5V9.5h2V9H5V8h3V10.5z M10.5,14.5h-1v-1h1 V14.5z M10.5,11.83h-1v-1h1V11.83z M10.5,9.17h-1v-1h1V9.17z M10.5,6.5h-1v-1h1V6.5z M15,8v4h-3V8H15z"/></g></svg>