<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M16.54,16.54L3.46,3.46c-0.29-0.29-0.77-0.29-1.06,0l0,0c-0.29,0.29-0.29,0.77,0,1.06L3,5.12V8c1.1,0,2,0.9,2,2s-0.9,2-2,2 v3.5C3,16.33,3.67,17,4.5,17H8c0-1.1,0.9-2,2-2s2,0.9,2,2h2.88l0.6,0.6c0.29,0.29,0.77,0.29,1.06,0l0,0 C16.83,17.31,16.83,16.83,16.54,16.54z M19,10c0,1.1-0.9,2-2,2v2.88L5.12,3H8c0-1.1,0.9-2,2-2s2,0.9,2,2h3.5C16.33,3,17,3.67,17,4.5 V8C18.1,8,19,8.9,19,10z"/></svg>