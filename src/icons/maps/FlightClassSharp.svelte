<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M14.5,4H10v6.75h4.5V4z M8.4,13H15v1.5H7.29L5,7V4h1.5v3L8.4,13z M7.5,15.5H15V17H7.5V15.5z"/></svg>