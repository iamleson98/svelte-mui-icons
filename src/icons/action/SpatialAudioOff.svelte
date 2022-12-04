<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><circle cx="8" cy="8" r="3"/><path d="M13.03,13.37C11.56,12.5,9.84,12,8,12s-3.56,0.5-5.03,1.37C2.36,13.72,2,14.39,2,15.09V17h12v-1.91 C14,14.39,13.64,13.72,13.03,13.37z"/><path d="M16.66,1L15.6,2.06c2.53,2.53,2.53,6.66,0,9.19l1.06,1.06C19.78,9.19,19.78,4.12,16.66,1z"/><path d="M14.54,3.12l-1.06,1.06c1.36,1.36,1.36,3.59,0,4.95l1.06,1.06C16.49,8.24,16.49,5.07,14.54,3.12z"/></g></g></svg>