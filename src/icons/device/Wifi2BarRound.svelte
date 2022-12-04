<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g display="none"><rect display="inline" fill={color} height={size} width={size}/></g><g><path d="M10,13c-0.83,0-1.5,0.67-1.5,1.5S9.17,16,10,16s1.5-0.67,1.5-1.5S10.83,13,10,13z M4.33,11.33 c0.35,0.35,0.89,0.39,1.29,0.1C6.85,10.53,8.36,10,10,10s3.15,0.53,4.39,1.43c0.4,0.29,0.94,0.24,1.29-0.1 c0.43-0.43,0.39-1.16-0.11-1.52C14,8.67,12.08,8,10,8S6,8.67,4.43,9.81C3.94,10.17,3.89,10.89,4.33,11.33z"/></g></svg>