<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M16.5,10v6.5h-13V9.47L6,8.33v1.71l4-1.75V10H16.5z M14,11.5h-1.5V15H14V11.5z M7.5,11.5H6V15h1.5V11.5z M10.75,11.5h-1.5V15h1.5V11.5z" opacity=".3"/><path d="M16.5,10v6.5h-13V9.47L6,8.33v1.71l4-1.75V10H16.5z M15,2l-1,6.5h-2.5V6l-4,1.75V6L2,8.5V18h16V8.5L17,2H15z M14,11.5h-1.5 V15H14V11.5z M7.5,11.5H6V15h1.5V11.5z M10.75,11.5h-1.5V15h1.5V11.5z"/></g></svg>