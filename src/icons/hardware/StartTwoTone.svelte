<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M13.12,5.62L17.5,10l-4.38,4.38l-1.06-1.06l2.56-2.56H5.5v-1.5h9.13L12.07,6.7L13.12,5.62z M2.5,5v10H4V5H2.5z"/></svg>