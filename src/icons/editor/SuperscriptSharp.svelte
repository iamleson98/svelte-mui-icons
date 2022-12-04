<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/><path d="M16,6v1h2v1l-3,0V5l2,0l0-1h-2V3l3,0v3L16,6z M5.63,16h1.9l2.43-3.87h0.08L12.47,16h1.9l-3.32-5.2l3.1-4.8h-1.91 l-2.19,3.56H9.96L7.75,6h-1.9l3.09,4.8L5.63,16z"/></g></svg>