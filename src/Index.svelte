<script>
  export let d;
  export let fill = "currentColor";
  export let stroke = undefined;
  export let title = undefined;

  let classProp;
  export { classProp as class };
</script>

<svg viewBox="0 0 24 24" class={classProp} {...$$restProps}>
  {#if title}<title>{title}</title>{/if}
  <path {fill} {stroke} {d} />
</svg>

<style>
svg {
  display: inline-block;
  vertical-align: middle;
}
</style>
