<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M17.5,4h-2v6h-1V1.25h-2V10h-1V0l-2,0v10h-1V1.5h-2v11H6.25l-1.99-5L1.93,8.42l2.96,7.44C5.89,18.36,8.31,20,11,20l0,0 c3.59,0,6.5-2.91,6.5-6.5V4z"/></svg>