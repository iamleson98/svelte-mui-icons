<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M17.5,3v1.5h-1.75V3h-1.5v1.5H12.5V3H11v3l2,2v1H7V8l2-2V3H7.5v1.5H5.75V3h-1.5v1.5H2.5V3H1v3l2,2v4l-2,2v3h7v-2 c0-1.1,0.9-2,2-2s2,0.9,2,2v2h7v-3l-2-2V8l2-2V3H17.5z"/></g></g></svg>