<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/></g><g><path d="M16,15.5V3H4v12.5H2V17h8.5c0,0.69,0.56,1.25,1.25,1.25S13,17.69,13,17h5v-1.5H16z M14.5,9.25h-2v-1.5h2V9.25z M11,9.25 H5.5v-1.5H11V9.25z M11,10.75v1.5H5.5v-1.5H11z M12.5,10.75h2v1.5h-2V10.75z M14.5,6.25h-2V4.5h2V6.25z M11,4.5v1.75H5.5V4.5H11z M5.5,15.5v-1.75H11v1.75H5.5z M12.5,15.5v-1.75h2v1.75H12.5z"/></g></svg>