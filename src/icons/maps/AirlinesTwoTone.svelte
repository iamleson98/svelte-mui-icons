<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M11.54,5.5l-6.19,9h8.65l1.69-9H11.54z M11.88,11.75c-1.04,0-1.88-0.84-1.88-1.88S10.84,8,11.88,8 s1.88,0.84,1.88,1.88S12.91,11.75,11.88,11.75z" opacity=".3"/><path d="M14.01,14.5H5.35l6.19-9h4.15L14.01,14.5z M10.75,4L2.5,16h12.75L17.5,4H10.75z M11.88,8C10.84,8,10,8.84,10,9.88 s0.84,1.88,1.88,1.88s1.88-0.84,1.88-1.88S12.91,8,11.88,8z"/></svg>