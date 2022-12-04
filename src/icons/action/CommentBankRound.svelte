<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M16.5,2h-13C2.67,2,2,2.67,2,3.5v13.29c0,0.45,0.54,0.67,0.85,0.35L5,15h11.5c0.83,0,1.5-0.67,1.5-1.5v-10 C18,2.67,17.33,2,16.5,2z M14.28,9.64L13,9l-1.28,0.64C11.39,9.8,11,9.56,11,9.19V4h4v5.19C15,9.56,14.61,9.8,14.28,9.64z"/></svg>