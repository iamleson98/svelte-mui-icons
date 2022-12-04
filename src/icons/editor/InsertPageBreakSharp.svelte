<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><rect height="4.5" width={size} x="4" y="13.5"/><path d="M16,6l-4-4H4v8h12V6z M11,7V3l4,4H11z"/><rect height="1.5" width={size} x="8" y="11"/><rect height="1.5" width={size} x="2" y="11"/><rect height="1.5" width={size} x="14" y="11"/></g></g></svg>