<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 24 24" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M14,2H4.01L4,22h16V8L14,2z M15,11h-4v1h4v5h-2v1h-2v-1H9v-2h4v-1H9V9h2V8h2v1h2V11z"/></svg>