<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><g><path d="M8,15c0,0.55,0.45,1,1,1h2c0.55,0,1-0.45,1-1v-5H8V15z"/></g><g><path d="M14,4l-2,2V4H8C6.34,4,5,5.34,5,7h3v2h4V7l2,2h1V4H14z"/></g></g></g></svg>