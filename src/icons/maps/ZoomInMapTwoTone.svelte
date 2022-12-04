<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M5.44,6.5L3,4.06L4.06,3L6.5,5.44V4H8v4H4V6.5H5.44z M16,8V6.5h-1.44L17,4.06L15.94,3L13.5,5.44V4H12v4H16z M4.06,17 l2.44-2.44V16H8v-4H4v1.5h1.44L3,15.94L4.06,17z M13.5,14.56L15.94,17L17,15.94l-2.44-2.44H16V12h-4v4h1.5V14.56z"/></g></svg>