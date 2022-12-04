<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><g><path d="M16,12v1h-1.59l2.46,2.46C16.95,15.32,17,15.17,17,15V5c0-0.55-0.45-1-1-1H5.41l8,8H16z"/><path d="M2.93,2.93L2.22,3.64l0.9,0.9C3.05,4.68,3,4.83,3,5v10c0,0.55,0.45,1,1,1h10.59l1.78,1.78l0.71-0.71L2.93,2.93z M8,12 h2.59l1,1H8V12z M4,12h3v1H4V12z M12,15H4v-1h8V15z"/></g></g></g></svg>