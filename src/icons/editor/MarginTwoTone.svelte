<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 24 24" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M5,19h14V5H5V19z M15,7h2v2h-2V7z M15,11h2v2h-2V11z M11,7h2v2h-2V7z M11,11h2v2h-2V11z M7,7h2v2H7V7z M7,11h2v2H7V11z" opacity=".3"/><rect height={size} width={size} x="7" y="7"/><rect height={size} width={size} x="7" y="11"/><path d="M3,3v18h18V3H3z M19,19H5V5h14V19z"/><rect height={size} width={size} x="11" y="7"/><rect height={size} width={size} x="15" y="11"/><rect height={size} width={size} x="11" y="11"/><rect height={size} width={size} x="15" y="7"/></g></g></svg>