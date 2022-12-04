<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 24 24" height={size} {viewBox} width={size}><rect fill={color} height={size} transform="matrix(-1 -1.224647e-16 1.224647e-16 -1 24 24)" width={size}/><polyline opacity=".3" points="15.5,15.38 15.5,8.62 18.88,12 15.5,15.38"/><path d="M15.5,15.38V8.62L18.88,12L15.5,15.38 M14,19l7-7l-7-7V19L14,19z M10,19V5l-7,7L10,19z"/></svg>