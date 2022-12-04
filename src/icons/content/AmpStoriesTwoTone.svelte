<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g/><g><g opacity=".3"><rect height={size} width={size} x="7" y="5"/></g><path d="M6,15h8V4H6V15z M7,5h6v9H7V5z"/><rect height={size} width={size} x="3" y="5"/><rect height={size} width={size} x="16" y="5"/></g></g></svg>