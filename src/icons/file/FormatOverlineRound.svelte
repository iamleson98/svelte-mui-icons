<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M15,3.75c0,0.41-0.34,0.75-0.75,0.75h-8.5C5.34,4.5,5,4.16,5,3.75S5.34,3,5.75,3h8.5C14.66,3,15,3.34,15,3.75z M15.5,11.5 c0,3.04-2.46,5.5-5.5,5.5s-5.5-2.46-5.5-5.5C4.5,8.46,6.96,6,10,6S15.5,8.46,15.5,11.5z M13.5,11.5C13.5,9.57,11.93,8,10,8 s-3.5,1.57-3.5,3.5S8.07,15,10,15S13.5,13.43,13.5,11.5z"/></g></svg>