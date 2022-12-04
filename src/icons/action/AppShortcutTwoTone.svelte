<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><rect height={size} opacity=".3" width={size} x="5.5" y="2.5"/><rect height={size} opacity=".3" width={size} x="5.5" y="16.5"/><path d="M14.5,15h-9V5h9v1H16V2.5C16,1.67,15.33,1,14.5,1h-9C4.67,1,4,1.67,4,2.5v15C4,18.33,4.67,19,5.5,19h9 c0.83,0,1.5-0.67,1.5-1.5V14h-1.5V15z M5.5,2.5h9v1h-9V2.5z M14.5,17.5h-9v-1h9V17.5z"/><polygon points="17.03,7.97 17.5,9 17.97,7.97 19,7.5 17.97,7.03 17.5,6 17.03,7.03 16,7.5"/><polygon points="13,7 12.06,9.06 10,10 12.06,10.94 13,13 13.94,10.94 16,10 13.94,9.06"/><polygon points="17.5,11 17.03,12.03 16,12.5 17.03,12.97 17.5,14 17.97,12.97 19,12.5 17.97,12.03"/></g></g></svg>