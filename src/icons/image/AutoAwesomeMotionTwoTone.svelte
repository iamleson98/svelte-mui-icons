<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 24 24" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/></g><g><g><rect height={size} opacity=".3" width={size} x="12" y="12"/><path d="M14,2H4C2.9,2,2,2.9,2,4v10h2V4h10V2z"/><path d="M20,10h-8c-1.1,0-2,0.9-2,2v8c0,1.1,0.9,2,2,2h8c1.1,0,2-0.9,2-2v-8C22,10.9,21.1,10,20,10z M20,20h-8v-8h8V20z"/><path d="M18,6H8C6.9,6,6,6.9,6,8v10h2V8h10V6z"/></g></g></svg>