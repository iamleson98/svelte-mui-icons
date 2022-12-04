<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M10.75,4L2.5,16h12.75L17.5,4H10.75z M11.88,11.75c-1.04,0-1.88-0.84-1.88-1.88S10.84,8,11.88,8s1.88,0.84,1.88,1.88 S12.91,11.75,11.88,11.75z"/></svg>