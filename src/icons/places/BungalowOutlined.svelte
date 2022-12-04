<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M10.75,11.5h-1.5V10h1.5V11.5z M16,12.6l-1.27,0.8L14,12.23V17H6v-4.77L5.27,13.4L4,12.6L10,3L16,12.6z M12.5,9.83l-2.5-4 l-2.5,4v5.67h1.75V13h1.5v2.5h1.75V9.83z"/></svg>