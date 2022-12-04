<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M4,12.25V15c0,1.66,1.34,3,3,3h6c1.66,0,3-1.34,3-3v-2.75H4z"/><path d="M16,10.75V8c0-1.3-0.84-2.4-2-2.82V2H6v3.18C4.84,5.6,4,6.7,4,8v2.75H16z M7.5,3.5h5V5h-1.75V4.25h-1.5V5H7.5V3.5z"/></g></g></svg>