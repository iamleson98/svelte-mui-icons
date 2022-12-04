<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M17,13.08L9.71,7.24l-3.03,4.15L3,8.62V6l3,2l4-5l4,3h3V13.08z M17,15l-7-5.61L7,13.5l-4-3V16h14V15z"/></svg>