<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><g><polygon points="16,12 16,13 14.41,13 17,15.59 17,4 5.41,4 13.41,12"/><path d="M2.93,2.93L2.22,3.64L3,4.41V16h11.59l1.78,1.78l0.71-0.71L2.93,2.93z M8,12h2.59l1,1H8V12z M4,12h3v1H4V12z M12,15H4v-1 h8V15z"/></g></g></g></svg>