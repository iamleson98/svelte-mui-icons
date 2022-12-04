<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M8,15v-4.5h4V15H8z M13,9.5h4V5h-4V9.5z M8,5v4.5h4V5H8z M7,9.5V5H3v4.5H7z M13,10.5V15h4v-4.5H13z M7,10.5H3V15h4V10.5z"/></svg>