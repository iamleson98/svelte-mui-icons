<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/></g><g><g/><g><path d="M14,15H5V6h6V5H5C4.45,5,4,5.45,4,6V15c0,0.55,0.45,1,1,1H14c0.55,0,1-0.45,1-1V9h-1V15z"/><polygon points="7,8 7,9 11,9 12,9 12,8"/><rect height={size} width={size} x="7" y="10"/><rect height={size} width={size} x="7" y="12"/><polygon points="15,3 14,3 14,5 14,5 12,5 12,6 14,6 14,8 15,8 15,6 15,6 17,6 17,5 15,5"/></g></g></svg>