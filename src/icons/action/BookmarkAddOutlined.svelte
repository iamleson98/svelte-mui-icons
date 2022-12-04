<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M13.5,9v5.78l-3.5-1.4l-3.5,1.4V4.5H11V3H6.5C5.67,3,5,3.67,5,4.5V17l5-2l5,2V9H13.5z M15.75,4.25v-1.5h-1.5v1.5h-1.5v1.5 h1.5v1.5h1.5v-1.5h1.5v-1.5H15.75z"/></svg>