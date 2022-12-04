<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M16,4H4v12h12V4z M6,7.27h3v1H6V7.27z M10,12.5H8.5V14h-1v-1.5H6v-1h1.5V10h1v1.5H10V12.5z M14,13.25h-3v-1h3V13.25z M14,11.75h-3v-1h3V11.75z M14.27,8.83l-0.71,0.71L12.5,8.47l-1.06,1.06l-0.71-0.71l1.06-1.06l-1.06-1.06L11.44,6l1.06,1.06 L13.56,6l0.71,0.71l-1.06,1.06L14.27,8.83z"/></g></g></svg>