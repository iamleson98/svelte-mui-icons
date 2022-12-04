<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M14,17.74V13.5h4.24V15h-1.68l2.21,2.21l-1.06,1.06l-2.21-2.21v1.68H14z M12,2H4v16h8.5v-6H16V6L12,2z M11,7V3l4,4H11z"/></g></svg>