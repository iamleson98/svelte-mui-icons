<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M15.25,14c0.96,0,1.75-0.79,1.75-1.75c0-1.16-1.75-3.06-1.75-3.06s-1.75,1.9-1.75,3.06C13.5,13.21,14.29,14,15.25,14z"/><rect height={size} width={size} x="2" y="16"/><path d="M7.03,12.6C7.3,12.87,7.65,13,8,13s0.7-0.13,0.97-0.4l3.63-3.63c0.53-0.53,0.53-1.4,0-1.93L5.57,0L4.51,1.06l2.43,2.43 L3.4,7.03c-0.53,0.53-0.53,1.4,0,1.93L7.03,12.6z M8,4.56L11.44,8H4.56L8,4.56z"/></g></g></svg>