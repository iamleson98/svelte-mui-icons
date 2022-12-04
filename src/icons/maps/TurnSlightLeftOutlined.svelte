<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/></g><g><path d="M12.5,10.56V16H11v-5.44l-4-4l0,1.69H5.5L5.5,4l4.25,0v1.5l-1.69,0l4,4C12.34,9.78,12.5,10.16,12.5,10.56z"/></g></svg>