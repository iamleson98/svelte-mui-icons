<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M19.74,8.05l-6.8-6.8l-2.4,2.4l4.72,4.71l-2.26,2.26L8.88,6.49l-5.12,5.12l1.13,1.13l4.36-4.35l0.57,0.57l-4.36,4.35 l1.13,1.13l4.36-4.35l0.57,0.57L7.16,15l1.13,1.13l4.36-4.35l0.57,0.57L8.85,16.7l1.13,1.13L19.74,8.05z M7.03,1.26L0.26,8.03 L3.23,11l5.64-5.64l4.14,4.14l1.14-1.14L7.03,1.26z"/></g></svg>