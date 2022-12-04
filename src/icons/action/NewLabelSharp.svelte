<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M17,10l-4,5h-2.5v-4.5h-2v-2H4V5h9L17,10z M9,12H7v-2H5.5v2h-2v1.5h2v2H7v-2h2V12z"/></svg>