<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} y="0"/><g><path d="M17.07,17.07L2.93,2.93L2.22,3.64L4,5.41V16h10.59l1.78,1.78L17.07,17.07z M6,14l2-2.67l1.35,1.81l1.05-1.32L12.59,14H6z M16,14.59L5.41,4H16V14.59z"/></g></g></svg>