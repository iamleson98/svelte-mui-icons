<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M16.5,2h-13C2.67,2,2,2.67,2,3.5V18l3-3h11.5c0.83,0,1.5-0.67,1.5-1.5v-10C18,2.67,17.33,2,16.5,2z M14.5,11l-2-1.8V11 c0,0.55-0.45,1-1,1h-5c-0.55,0-1-0.45-1-1V6c0-0.55,0.45-1,1-1h5c0.55,0,1,0.45,1,1v1.8l2-1.8V11z"/></g></svg>