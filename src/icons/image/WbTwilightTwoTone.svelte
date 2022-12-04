<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><rect height="1.5" width={size} x="2" y="14.5"/><rect height="2.5" width="1.5" x="9.25" y="3"/><rect height="1.5" transform="matrix(0.7071 -0.7071 0.7071 0.7071 -0.1972 12.8523)" width="2.5" x="14.16" y="5.91"/><rect height="2.5" transform="matrix(0.7071 -0.7071 0.7071 0.7071 -3.3852 5.1557)" width="1.5" x="3.78" y="5.41"/><path d="M10,7c-3.31,0-6,2.69-6,6h12C16,9.69,13.31,7,10,7z"/></g></g></svg>