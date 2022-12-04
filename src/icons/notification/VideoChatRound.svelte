<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M16.5,2h-13C2.67,2,2,2.67,2,3.5v13.29c0,0.45,0.54,0.67,0.85,0.35L5,15h11.5c0.83,0,1.5-0.67,1.5-1.5v-10 C18,2.67,17.33,2,16.5,2z M13.67,10.25L12.5,9.2V11c0,0.55-0.45,1-1,1h-5c-0.55,0-1-0.45-1-1V6c0-0.55,0.45-1,1-1h5 c0.55,0,1,0.45,1,1v1.8l1.17-1.05c0.32-0.29,0.83-0.06,0.83,0.37v2.75C14.5,10.31,13.99,10.54,13.67,10.25z"/></g></svg>