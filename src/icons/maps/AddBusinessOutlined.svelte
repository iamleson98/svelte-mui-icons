<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/></g><g><g><rect height={size} width={size} x="4" y="4"/><path d="M13,14h1v-3h1v-1l-1-4H4l-1,4v1h1v5h6v-5h3V14z M9,15H5v-4h4V15z M4.03,10l0.75-3h8.44l0.75,3H4.03z"/><polygon points="18,15 16,15 16,13 15,13 15,15 13,15 13,16 15,16 15,18 16,18 16,16 18,16"/></g></g></svg>