<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 24 24" height={size} {viewBox} width={size}><g><path d="M0,0h24v24H0V0z" fill={color}/></g><g><g><path d="M3,7h2v7H3V7z M0,10h2v7H0V10z M22,7h2v7h-2V7z M19,10h2v7h-2V10z M16,2.01L8,2C6.9,2,6,2.9,6,4v16c0,1.1,0.9,2,2,2h8 c1.1,0,2-0.9,2-2V4C18,2.9,17.1,2.01,16,2.01z M16,20H8v-1h8V20z M16,17H8V7h8V17z M8,5V4h8v1H8z"/></g></g></svg>