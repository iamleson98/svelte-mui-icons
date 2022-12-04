<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M4,16.5C4,17.33,4.67,18,5.5,18h9c0.83,0,1.5-0.67,1.5-1.5v-3H4V16.5z"/><path d="M16,6l-4-4H5.5C4.67,2,4,2.67,4,3.5V10h12V6z M11,7V3l4,4H11z"/><rect height="1.5" width={size} x="8" y="11"/><rect height="1.5" width={size} x="2" y="11"/><rect height="1.5" width={size} x="14" y="11"/></g></g></svg>