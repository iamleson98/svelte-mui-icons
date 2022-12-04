<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/></g><g><path d="M7.5,10.56V16H9v-5.44l4-4l0,1.69h1.5l0-4.25l-4.25,0v1.5l1.69,0l-4,4C7.66,9.78,7.5,10.16,7.5,10.56z"/></g></svg>