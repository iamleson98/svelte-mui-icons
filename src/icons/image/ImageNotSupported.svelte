<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} y="0"/><g><path d="M5.41,4H15c0.55,0,1,0.45,1,1v9.59L5.41,4z M16.36,17.78L14.59,16H5c-0.55,0-1-0.45-1-1V5.41L2.22,3.64l0.71-0.71 l14.14,14.14L16.36,17.78z M12.59,14l-2.18-2.18l-1.05,1.32L8,11.33L6,14H12.59z"/></g></g></svg>