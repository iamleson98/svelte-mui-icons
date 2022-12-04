<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/></g><g><g><path d="M16,4H4C3.45,4,3,4.45,3,5v10c0,0.55,0.45,1,1,1h12c0.55,0,1-0.45,1-1V5 C17,4.45,16.55,4,16,4z M16,15H4V5h12V15z" fill-rule="evenodd"/><rect fill-rule="evenodd" height={size} width={size} x="5" y="7"/><rect fill-rule="evenodd" height={size} width={size} x="5" y="9.5"/><rect fill-rule="evenodd" height={size} width={size} x="5" y="12"/><polygon fill-rule="evenodd" points="11.97,11.77 14.8,8.94 14.1,8.23 11.97,10.35 11.27,9.65 10.56,10.35"/></g></g></svg>