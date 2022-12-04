<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M10,3l-6,9.6l1.27,0.8L6,12.23V17h3.25v-4h1.5v4H14v-4.77l0.73,1.16L16,12.6L10,3z M10.75,11.5h-1.5V10h1.5V11.5z"/></svg>