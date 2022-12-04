<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} y="0"/><g><path d="M16.72,16.72L3.28,3.28c-0.2-0.2-0.51-0.2-0.71,0s-0.2,0.51,0,0.71L4,5.41V15c0,0.55,0.45,1,1,1h9.59l1.42,1.42 c0.2,0.2,0.51,0.2,0.71,0S16.91,16.91,16.72,16.72z M6,14l2-2.67l1.35,1.81l1.05-1.32L12.59,14H6z M16,14.59L5.41,4H15 c0.55,0,1,0.45,1,1V14.59z"/></g></g></svg>