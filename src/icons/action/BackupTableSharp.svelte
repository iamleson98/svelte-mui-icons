<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><g><polygon points="16,6 16,16 6,16 6,17 17,17 17,6"/></g><g><path d="M14,14V3H3v11H14z M4,4h9v4H4V4z M8,13H4V9h4V13z M9,9h4v4H9V9z"/></g></g></g></svg>