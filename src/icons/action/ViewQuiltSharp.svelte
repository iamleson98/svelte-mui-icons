<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M8,15v-4.5h4V15H8z M8,5v4.5h9V5H8z M7,15V5H3v10H7z M13,10.5V15h4v-4.5H13z"/></svg>