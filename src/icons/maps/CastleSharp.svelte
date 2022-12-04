<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M17.5,7v2H16V2h-1.5v2h-2V2H11v2H9V2H7.5v2h-2V2H4v7H2.5V7H1v10h7v-4h4v4h7V7H17.5z M9,10H7.5V7H9V10z M12.5,10H11V7h1.5 V10z"/></g></g></svg>