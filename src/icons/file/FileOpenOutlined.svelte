<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/></g><g><path d="M14,17.74V13.5h4.24V15h-1.68l2.21,2.21l-1.06,1.06l-2.21-2.21v1.68H14z M12.5,16.5h-7v-13H11V7h3.5v5H16V6l-4-4H5.5 C4.67,2,4,2.67,4,3.5v13C4,17.33,4.67,18,5.5,18h7V16.5z"/></g></svg>