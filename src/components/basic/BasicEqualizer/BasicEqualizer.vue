<template>
  <svg viewBox="0 0 32 32">
    <rect width="10" height="32" />
    <rect width="10" height="32" x="11" />
    <rect width="10" height="32" x="22" />
  </svg>
</template>

<script>
export default {};
</script>

<style scoped>
@media (prefers-reduced-motion: reduce) {
  rect {
    animation: none;
  }
}

svg {
  transform: rotate(180deg);
  --two: calc((1 / 7));
  --three: calc((1 / 4.666666667));
  --four: calc((1 / 3.5));
  --five: calc((1 / 2.8));
  --six: calc((1 / 2.333333333));
  --seven: calc((1 / 2));
  --eight: calc((1 / 1.75));
  --nine: calc((1 / 1.555555556));
  --ten: calc((1 / 1.4));
  --eleven: calc((1 / 1.272727273));
  --twelve: calc((1 / 1.166666667));
  --thirteen: calc((1 / 1.076923077));
  --fourteen: 1;
}

rect {
  animation-duration: 1.25s;
  animation-iteration-count: infinite;
  animation-timing-function: steps(25, end);
}

rect:nth-of-type(3) {
  transform: scaleY(var(--four));
  animation-name: equalize1;
}
rect:nth-of-type(2) {
  transform: scaleY(var(--twelve));
  animation-name: equalize2;
}
rect:nth-of-type(1) {
  transform: scaleY(var(--nine));
  animation-name: equalize3;
}

@keyframes equalize1 {
  0% {
    transform: scaleY(var(--four));
  }
  4% {
    transform: scaleY(var(--two));
  }
  8% {
    transform: scaleY(var(--four));
  }
  12% {
    transform: scaleY(var(--seven));
  }
  16% {
    transform: scaleY(var(--ten));
  }
  20% {
    transform: scaleY(var(--thirteen));
  }
  24% {
    transform: scaleY(var(--twelve));
  }
  28% {
    transform: scaleY(var(--eleven));
  }
  32% {
    transform: scaleY(var(--eleven));
  }
  36% {
    transform: scaleY(var(--eight));
  }
  40% {
    transform: scaleY(var(--ten));
  }
  44% {
    transform: scaleY(var(--ten));
  }
  48% {
    transform: scaleY(var(--eleven));
  }
  52% {
    transform: scaleY(var(--twelve));
  }
  56% {
    transform: scaleY(var(--thirteen));
  }
  60% {
    transform: scaleY(var(--twelve));
  }
  64% {
    transform: scaleY(var(--twelve));
  }
  68% {
    transform: scaleY(var(--eleven));
  }
  72% {
    transform: scaleY(var(--ten));
  }
  76% {
    transform: scaleY(var(--eleven));
  }
  80% {
    transform: scaleY(var(--twelve));
  }
  84% {
    transform: scaleY(var(--twelve));
  }
  88% {
    transform: scaleY(var(--thirteen));
  }
  92% {
    transform: scaleY(var(--ten));
  }
  96% {
    transform: scaleY(var(--seven));
  }
  100% {
    transform: scaleY(var(--four));
  }
}

@keyframes equalize2 {
  0% {
    transform: scaleY(var(--twelve));
  }
  4% {
    transform: scaleY(var(--thirteen));
  }
  8% {
    transform: scaleY(var(--twelve));
  }
  12% {
    transform: scaleY(var(--twelve));
  }
  16% {
    transform: scaleY(var(--eleven));
  }
  20% {
    transform: scaleY(var(--eleven));
  }
  24% {
    transform: scaleY(var(--eleven));
  }
  28% {
    transform: scaleY(var(--twelve));
  }
  32% {
    transform: scaleY(var(--twelve));
  }
  36% {
    transform: scaleY(var(--thirteen));
  }
  40% {
    transform: scaleY(var(--thirteen));
  }
  44% {
    transform: scaleY(var(--thirteen));
  }
  48% {
    transform: scaleY(var(--eleven));
  }
  52% {
    transform: scaleY(var(--eight));
  }
  56% {
    transform: scaleY(var(--six));
  }
  60% {
    transform: scaleY(var(--eight));
  }
  64% {
    transform: scaleY(var(--ten));
  }
  68% {
    transform: scaleY(var(--eleven));
  }
  72% {
    transform: scaleY(var(--thirteen));
  }
  76% {
    transform: scaleY(var(--twelve));
  }
  80% {
    transform: scaleY(var(--twelve));
  }
  84% {
    transform: scaleY(var(--twelve));
  }
  88% {
    transform: scaleY(var(--eleven));
  }
  92% {
    transform: scaleY(var(--nine));
  }
  96% {
    transform: scaleY(var(--eleven));
  }
  100% {
    transform: scaleY(var(--twelve));
  }
}

@keyframes equalize3 {
  0% {
    transform: scaleY(var(--nine));
  }
  4% {
    transform: scaleY(var(--seven));
  }
  8% {
    transform: scaleY(var(--nine));
  }
  12% {
    transform: scaleY(var(--eleven));
  }
  16% {
    transform: scaleY(var(--thirteen));
  }
  20% {
    /* transform: scaleY(var(--eleven)); TODO */
  }
  24% {
    transform: scaleY(var(--fourteen));
  }
  28% {
    transform: scaleY(var(--eleven));
  }
  32% {
    transform: scaleY(var(--nine));
  }
  36% {
    transform: scaleY(var(--eight));
  }
  40% {
    transform: scaleY(var(--seven));
  }
  44% {
    transform: scaleY(var(--five));
  }
  48% {
    transform: scaleY(var(--eight));
  }
  52% {
    transform: scaleY(var(--ten));
  }
  56% {
    transform: scaleY(var(--eleven));
  }
  60% {
    transform: scaleY(var(--thirteen));
  }
  64% {
    transform: scaleY(var(--twelve));
  }
  68% {
    transform: scaleY(var(--eleven));
  }
  72% {
    transform: scaleY(var(--eleven));
  }
  76% {
    transform: scaleY(var(--ten));
  }
  80% {
    transform: scaleY(var(--twelve));
  }
  84% {
    transform: scaleY(var(--thirteen));
  }
  88% {
    transform: scaleY(var(--fourteen));
  }
  92% {
    transform: scaleY(var(--twelve));
  }
  96% {
    transform: scaleY(var(--ten));
  }
  100% {
    transform: scaleY(var(--nine));
  }
}
</style>
