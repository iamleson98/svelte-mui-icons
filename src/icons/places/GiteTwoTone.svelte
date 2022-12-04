<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M3.5,13.5V10h8v3.5H3.5z M16.5,13.5H13V9.12l1.75-1.75l1.75,1.75V13.5z" opacity=".3"/><path d="M18,8.5l-3-3c0,0,0,0,0,0H7.5V4H6v1.5H5l-3,3V15c0,0,0,0,0,0h9.5H13h5c0,0,0,0,0,0L18,8.5C18,8.5,18,8.5,18,8.5z M3.5,13.5 V10h8v3.5H3.5z M16.5,13.5H13V9.12l1.75-1.75l1.75,1.75V13.5z"/></svg>