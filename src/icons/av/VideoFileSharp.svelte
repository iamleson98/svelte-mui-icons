<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M12,2H4v16h12V6L12,2z M13,14c0,0-0.78-0.55-1.5-1.05v1.55H7V10h4.5v1.55L13,10.5V14z M11,7V3l4,4H11z"/></g></svg>