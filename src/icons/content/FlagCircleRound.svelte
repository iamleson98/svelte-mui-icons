<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M10,2c-4.42,0-8,3.58-8,8s3.58,8,8,8s8-3.58,8-8S14.42,2,10,2z M14,12h-2.46c-0.33,0-0.65-0.17-0.83-0.45L10,10.5H8v4 C8,14.78,7.78,15,7.5,15h0C7.22,15,7,14.78,7,14.5V7c0-0.55,0.45-1,1-1h2.96c0.33,0,0.65,0.17,0.83,0.45l0.7,1.05H14 c0.55,0,1,0.45,1,1V11C15,11.55,14.55,12,14,12z"/></g></g></svg>