<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><polygon points="2.5,7 1,7 1,18 16,18 16,16.5 2.5,16.5"/><path d="M15,4V1H8v3H4v11h15V4H15z M9.5,2.5h4V4h-4V2.5z M10,12.5v-6l4.5,3L10,12.5z"/></g></g></svg>