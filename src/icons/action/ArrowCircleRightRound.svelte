<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M18,10c0-4.42-3.58-8-8-8s-8,3.58-8,8s3.58,8,8,8S18,14.42,18,10z M10,11.79v-1.04H7.75C7.34,10.75,7,10.41,7,10 s0.34-0.75,0.75-0.75H10V8.21c0-0.45,0.54-0.67,0.85-0.35l1.79,1.79c0.2,0.2,0.2,0.51,0,0.71l-1.79,1.79 C10.54,12.46,10,12.24,10,11.79z"/></g></svg>