<template>
  <div class="splash-screen">
    <img src="@/assets/cashflow-icon.svg" alt="CashFlow" />
    <h1><span>Cash</span>Flow</h1>
  </div>
</template>

<style>
.splash-screen {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100vh;
}

h1 {
  color: var(--brand-blue);
}

h1 span {
  color: var(--brand-green);
}
</style>
