<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><rect height={size} opacity=".3" width="2.67" x="8.67" y="13.5"/><rect height={size} opacity=".3" width="2.67" x="12.83" y="13.5"/><rect height={size} opacity=".3" width="2.67" x="4.5" y="13.5"/><path d="M6.06,7.19L4.87,6H14c0.83,0,1.5,0.67,1.5,1.5S14.83,9,14,9H3v1.5h11c1.65,0,3-1.35,3-3s-1.35-3-3-3H4.87l1.19-1.19 L5,2.25l-3,3l3,3L6.06,7.19z"/><path d="M3,17h14v-5H3V17z M12.83,13.5h2.67v2h-2.67V13.5z M8.67,13.5h2.67v2H8.67V13.5z M4.5,13.5h2.67v2H4.5V13.5z"/></g></g></svg>