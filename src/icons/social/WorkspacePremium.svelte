<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M10,2C6.41,2,3.5,4.91,3.5,8.5c0,1.83,0.76,3.48,1.97,4.66V19L10,18l4.5,1v-5.82c1.23-1.18,2-2.84,2-4.68 C16.5,4.91,13.59,2,10,2z M10,13.5c-2.76,0-5-2.24-5-5s2.24-5,5-5s5,2.24,5,5S12.76,13.5,10,13.5z M8.14,11.35L10,9.94l1.85,1.41 l-0.7-2.28L13,7.6h-2.27L10,5.35L9.27,7.6H7l1.85,1.47L8.14,11.35z"/></svg>