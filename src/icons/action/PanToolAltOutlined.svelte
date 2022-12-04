<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/></g><g><path d="M15.39,9.36L12.5,8h-1V5c0-1.1-0.9-2-2-2s-2,0.9-2,2v5.5l-1.18-0.29c-0.44-0.11-1-0.03-1.42,0.39L3.5,12l4.56,4.56 C8.34,16.84,8.72,17,9.12,17h5.26c0.75,0,1.38-0.55,1.48-1.29l0.61-4.29C16.6,10.57,16.16,9.74,15.39,9.36z M14.38,15.5H9.12 L5.62,12l0.34-0.34L9,12.42V5c0-0.28,0.22-0.5,0.5-0.5S10,4.72,10,5v4.5h2.15l2.58,1.2c0.19,0.1,0.3,0.3,0.27,0.52L14.38,15.5z"/></g></svg>