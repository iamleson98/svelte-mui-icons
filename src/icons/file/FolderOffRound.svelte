<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M2.75,2.75c-0.29-0.29-0.77-0.29-1.06,0c-0.29,0.29-0.29,0.77,0,1.06l0.69,0.69C2.15,4.77,2,5.12,2,5.5v9 C2,15.33,2.67,16,3.5,16h10.38l2.31,2.31c0.29,0.29,0.77,0.29,1.06,0c0.29-0.29,0.29-0.77,0-1.06L2.75,2.75z"/><path d="M16.5,6H10L8.44,4.44C8.16,4.16,7.78,4,7.38,4H6.12l11.49,11.49C17.85,15.23,18,14.88,18,14.5v-7C18,6.67,17.33,6,16.5,6z"/></g></g></svg>