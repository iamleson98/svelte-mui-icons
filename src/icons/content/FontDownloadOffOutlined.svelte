<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M9.7,7.58L8.56,6.44L9.1,5h1.79l2.27,6.04l-2.55-2.55l-0.57-1.63H9.95L9.7,7.58z M16.72,18.84L15.88,18H3.5 C2.67,18,2,17.33,2,16.5V4.12L1.16,3.28l1.06-1.06l15.56,15.56L16.72,18.84z M14.38,16.5l-4.06-4.06H7.99L7.08,15H5.35L7.4,9.52 l-3.9-3.9V16.5H14.38z M16.5,3.5v10.88l1.5,1.5V3.5C18,2.67,17.33,2,16.5,2H4.12l1.5,1.5H16.5z"/></svg>