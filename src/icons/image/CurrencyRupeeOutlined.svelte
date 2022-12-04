<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/></g><g><path d="M11.4,17h2.11l-5.4-5.5h0.65c2.26,0,4.11-1.77,4.24-4l1.51,0l0-1.5l-1.69,0c-0.17-0.56-0.46-1.07-0.82-1.5l2.51,0l0-1.5 l-9,0v1.5l3.25,0c1.07,0,1.99,0.61,2.45,1.5L5.5,6v1.5l5.99,0c-0.13,1.4-1.3,2.5-2.74,2.5L6,10v1.5L11.4,17z"/></g></svg>