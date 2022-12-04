<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M3.5,17.5H13V19H3.5C2.67,19,2,18.33,2,17.5V6h1.5V17.5z M17,5v9.5c0,0.83-0.67,1.5-1.5,1.5h-9C5.67,16,5,15.33,5,14.5v-12 C5,1.67,5.67,1,6.5,1H13L17,5z M13.25,11h-4.5v1.5h4.5V11z M13.25,6.5h-1.5V5h-1.5v1.5h-1.5V8h1.5v1.5h1.5V8h1.5V6.5z"/></g></svg>