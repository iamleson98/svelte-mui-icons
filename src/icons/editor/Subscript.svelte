<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/><path d="M17,15l-1,0v1h2v1h-3v-2c0-0.55,0.45-1,1-1l1,0l0-1h-2v-1l2,0c0.55,0,1,0.45,1,1v1C18,14.55,17.55,15,17,15z M5.63,14h1.9 l2.43-3.87h0.08L12.47,14h1.9l-3.32-5.2l3.1-4.8h-1.91l-2.19,3.56H9.96L7.75,4h-1.9l3.09,4.8L5.63,14z"/></g></svg>