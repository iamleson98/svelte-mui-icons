<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M3,5v10h14V5H3z M15.5,9.25h-2.67V6.5h2.67V9.25z M8.67,9.25V6.5h2.67v2.75H8.67z M11.33,10.75v2.75H8.67v-2.75H11.33z M7.17,6.5v2.75H4.5V6.5H7.17z M4.5,10.75h2.67v2.75H4.5V10.75z M12.83,13.5v-2.75h2.67v2.75H12.83z"/></svg>