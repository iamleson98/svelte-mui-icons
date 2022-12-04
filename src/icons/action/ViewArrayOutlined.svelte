<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M3,5h2v10H3V5z M15,5v10h2V5H15z M6,5h8v10H6V5z M7.5,13.5h5v-7h-5V13.5z"/></svg>