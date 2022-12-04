<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 24 24" height={size} {viewBox} width={size}><g><path d="M0,0h24v24H0V0z" fill={color}/></g><g><g><g><polygon points="6,5 4,5 4,23 16,23 16,21 6,21"/></g><g><path d="M20,1H8v18h12V1z M18,15h-8V5h8V15z"/></g><g><polygon points="12.5,10.25 14.5,10.25 14.5,12 17,9.5 14.5,7 14.5,8.75 11,8.75 11,12 12.5,12"/></g></g></g></svg>