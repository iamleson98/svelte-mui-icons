<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/></g><g><path d="M14.5,10.5c0,0.83-0.67,1.5-1.5,1.5l-6,0v5H5.5v-5c0-0.83,0.67-1.5,1.5-1.5l6,0l0-4.63l-1.19,1.19L10.75,6l3-3l3,3 l-1.06,1.06L14.5,5.87L14.5,10.5z"/></g></svg>