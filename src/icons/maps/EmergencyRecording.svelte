<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M18,6l-3,3V5.5C15,4.67,14.33,4,13.5,4h-9C3.67,4,3,4.67,3,5.5v9C3,15.33,3.67,16,4.5,16h9c0.83,0,1.5-0.67,1.5-1.5V11l3,3 V6z M10.5,10l2.25,1.3L12,12.6l-2.25-1.3v2.45h-1.5V11.3L6,12.6l-0.75-1.3L7.5,10L5.25,8.7L6,7.4l2.25,1.3V6.25h1.5V8.7L12,7.4 l0.75,1.3L10.5,10z"/></g></svg>