<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/></g><g><g><rect height="6.5" width="1.5" x="9.25" y="8"/><rect height="6.5" width="1.5" x="4" y="8"/><path d="M18,5l-8-4L2,5v2h16V5z M4.35,5.5L10,2.68l5.65,2.82H4.35z"/><path d="M2,15.5V17h10.66c-0.05-0.22-0.16-0.71-0.16-1.5H2z"/><polygon points="16,10.82 16,8 14.5,8 14.5,11.57"/><path d="M17,12l-3,1.5v2.14c0,2.02,1.28,3.91,3,4.36c1.72-0.46,3-2.35,3-4.36V13.5L17,12z M16.43,17.5l-1.55-1.54l0.71-0.71 l0.82,0.81L18.39,14l0.73,0.68L16.43,17.5z"/></g></g></svg>