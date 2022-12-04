<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size} x="0" y="0"/><path d="M10,4c3.31,0,6,2.69,6,6s-2.69,6-6,6s-6-2.69-6-6S6.69,4,10,4 M10,3c-3.86,0-7,3.14-7,7s3.14,7,7,7s7-3.14,7-7S13.86,3,10,3 L10,3z M10,13l4-3l-4-3V13z M8,7v6h1V7H8z"/></svg>