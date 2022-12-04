<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M16.5,6H10L8,4H3.5C2.67,4,2,4.67,2,5.5v9C2,15.33,2.67,16,3.5,16h13c0.83,0,1.5-0.67,1.5-1.5v-7C18,6.67,17.33,6,16.5,6z M15.5,10H15v2.5c0,0.55-0.45,1-1,1h-1.5c-0.55,0-1-0.45-1-1V10H11V9h1.5V8.5H14V9h1.5V10z M14,12.5h-1.5V10H14V12.5z"/></g></svg>