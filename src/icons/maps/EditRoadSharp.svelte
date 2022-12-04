<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><rect height={size} width={size} x="4" y="4"/><rect height={size} width={size} x="8.5" y="4"/><rect height={size} width={size} x="8.5" y="14"/><rect height={size} width={size} x="8.5" y="9"/><path d="M18.07,9.64l-0.71-0.71c-0.39-0.39-1.02-0.39-1.41,0L11,13.88V16h2.12l4.95-4.95C18.46,10.66,18.46,10.03,18.07,9.64z M12.71,15H12v-0.71l3.24-3.24l0.71,0.71L12.71,15z"/><polygon points="14,4 13,4 13,10.46 14,9.46"/></g></g></svg>