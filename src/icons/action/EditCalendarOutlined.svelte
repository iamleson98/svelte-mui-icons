<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M4.5,9h11v1H17V5.5C17,4.68,16.33,4,15.5,4H14V2h-1.5v2h-5V2H6v2H4.5C3.67,4,3,4.68,3,5.5v11C3,17.32,3.67,18,4.5,18h5v-1.5 h-5V9z M4.5,5.5h11v2h-11V5.5z M18.42,13.34l-0.65,0.65l-1.77-1.77l0.65-0.65c0.29-0.29,0.77-0.29,1.06,0l0.71,0.71 C18.72,12.58,18.72,13.05,18.42,13.34z M15.42,12.81l1.77,1.77L12.77,19H11v-1.77L15.42,12.81z"/></svg>