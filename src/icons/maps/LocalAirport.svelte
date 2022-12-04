<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/><path d="M17,13v-1l-6-4V4c0-0.55-0.45-1-1-1S9,3.45,9,4v4l-6,4v1l6-2v4l-1.5,1v1l2.5-0.5l2.5,0.5v-1L11,15v-4L17,13z"/></g></svg>