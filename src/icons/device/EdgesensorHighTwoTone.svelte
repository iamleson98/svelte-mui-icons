<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 24 24" height={size} {viewBox} width={size}><g><path d="M0,0h24v24H0V0z" fill={color}/></g><g><g><rect height={size} opacity=".3" width={size} x="8" y="4"/><rect height={size} opacity=".3" width={size} x="8" y="19"/><path d="M16,2.01L8,2C6.9,2,6,2.9,6,4v16c0,1.1,0.9,2,2,2h8c1.1,0,2-0.9,2-2V4C18,2.9,17.1,2.01,16,2.01z M16,20H8v-1h8V20z M16,17H8V7h8V17z M16,5H8V4h8V5z"/><rect height={size} width={size} x="19" y="10"/><rect height={size} width={size} x="22" y="7"/><rect height={size} width={size} x="3" y="7"/><rect height={size} width={size} y="10"/></g></g></svg>