<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M10,2L3.5,4.5v4.77c0,4.04,2.77,7.81,6.5,8.73c3.73-0.92,6.5-4.69,6.5-8.73V4.5L10,2z M13.06,11.76 c-1.43,1.69-4.05,1.63-5.41-0.06c-1.71-2.12-0.51-5.23,2.09-5.7c0.27-0.05,0.49,0.21,0.39,0.47c-0.36,0.95-0.3,2.05,0.25,3 s1.47,1.55,2.48,1.71C13.12,11.23,13.24,11.55,13.06,11.76z"/></g></svg>