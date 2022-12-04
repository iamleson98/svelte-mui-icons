<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M10,2c-4.42,0-8,3.58-8,8s3.58,8,8,8s8-3.58,8-8S14.42,2,10,2z M12.84,9.76l-2.13,2.13c-0.39,0.39-1.02,0.39-1.41,0 L7.16,9.76c-0.29-0.29-0.29-0.77,0-1.06c0.29-0.29,0.77-0.29,1.06,0L10,10.48l1.78-1.78c0.29-0.29,0.77-0.29,1.06,0 C13.13,8.99,13.13,9.47,12.84,9.76z"/></svg>