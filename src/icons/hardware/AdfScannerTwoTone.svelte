<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M3.5,14.5h13V11h-13V14.5z M14.75,12c0.41,0,0.75,0.34,0.75,0.75c0,0.41-0.34,0.75-0.75,0.75 S14,13.16,14,12.75C14,12.34,14.34,12,14.75,12z" opacity=".3"/><rect height={size} opacity=".3" width={size} x="6.5" y="5.5"/><g><path d="M16,9.5h-1V4H5v5.5H4c-1.1,0-2,0.9-2,2V16h16v-4.5C18,10.4,17.1,9.5,16,9.5z M6.5,5.5h7v4h-7V5.5z M16.5,14.5h-13V11h13 V14.5z"/></g><g><circle cx="14.75" cy="12.75" r=".75"/></g></g></g></svg>