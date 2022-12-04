<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><circle cx="10" cy="11.5" r="1.25"/><path d="M15.5,9H15V7h1V5.5h-1.25C14.11,3.48,12.24,2,10,2S5.89,3.48,5.25,5.5H4V7h1v2H4.5C3.67,9,3,9.67,3,10.5v2 C3,13.33,3.67,14,4.5,14H5v2.5H4V18h12v-1.5h-1V14h0.5c0.83,0,1.5-0.67,1.5-1.5v-2C17,9.67,16.33,9,15.5,9z M10,14.25 c-1.52,0-2.75-1.23-2.75-2.75S8.48,8.75,10,8.75s2.75,1.23,2.75,2.75S11.52,14.25,10,14.25z"/></g></g></svg>