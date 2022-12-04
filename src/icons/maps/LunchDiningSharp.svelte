<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M17.99,8c0.26-2.73-3.42-5-7.99-5C5.44,3,1.76,5.27,2.01,8H17.99z"/><rect height={size} width={size} x="2" y="13"/><path d="M15.34,9.25c-1.58,0-1.72,1-2.67,1c-0.95,0-1.08-1-2.67-1c-1.58,0-1.72,1-2.67,1c-0.95,0-1.09-1-2.67-1 c-1.58,0-1.72,1-2.67,1v1.5c1.58,0,1.72-1,2.67-1c0.95,0,1.09,1,2.67,1c1.58,0,1.72-1,2.67-1c0.95,0,1.08,1,2.67,1 c1.58,0,1.72-1,2.67-1c0.95,0,1.08,1,2.66,1v-1.5C17.05,10.25,16.92,9.25,15.34,9.25z"/></g></g></svg>