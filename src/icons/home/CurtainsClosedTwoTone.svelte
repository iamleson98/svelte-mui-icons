<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><rect height={size} opacity=".3" width={size} x="5.5" y="4.5"/><rect height={size} opacity=".3" width={size} x="12.5" y="4.5"/><path d="M16,15.5V3H4v12.5H2V17h16v-1.5H16z M7.5,15.5h-2v-11h2V15.5z M11,15.5H9v-11h2V15.5z M14.5,15.5h-2v-11h2V15.5z"/></g></g></svg>