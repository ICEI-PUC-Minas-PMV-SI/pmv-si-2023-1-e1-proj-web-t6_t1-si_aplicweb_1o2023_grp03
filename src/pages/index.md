---
permalink: /index.html
title: ' Cofrinho $'
layout: 'home'
---
<style>
.savings-calculator {
  max-width: 600px;
  margin: 0 auto;
  text-align: center;
  font-family: Arial, sans-serif;
}

h2 {
  margin-top: 0;
}

.input-group {
  margin-bottom: 10px;
}

label {
  display: inline-block;
  width: 120px;
  margin-right: 10px;
  font-weight: bold;
}

input[type="number"] {
  padding: 8px;
  border: none;
  border-radius: 3px;
  background-color: #ededed;
  width: 100%;
  max-width: 400px;
  box-sizing: border-box;
  font-size: 16px;
}

button {
  background-color: #008000;
  color: #fff;
  padding: 10px 20px;
  border: none;
  border-radius: 3px;
  cursor: pointer;
  transition: background-color 0.2s ease;
}

button:hover {
  background-color: #006400;
}

.result {
  margin-top: 20px;
  padding: 20px;
  border: 1px solid #f0f0f0;
  border-radius: 3px;
}

.result p {
  font-size: 20px;
  font-weight: bold;
  margin-bottom: 20px;
}

.result span {
  font-weight: bold;
}

#resultDiv {
  display: none;
}

.comparison {
  margin-top: 20px;
}

.comparison h3 {
  font-size: 20px;
  font-weight: bold;
  margin-bottom: 10px;
}

.row {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 10px;
}

.row span {
  font-weight: bold;
}

#six-months,
#one-year,
#two-years,
#five-years,
#ten-years,
#fifteen-years,
#thirty-years,
#six-months-investing,
#one-year-investing,
#two-years-investing,
#five-years-investing,
#ten-years-investing,
#fifteen-years-investing,
#thirty-years-investing {
  font-weight: bold;
  color: #008000;
}

.hidden {
  display: none;
}

</style>

<h2 style="text-align: center;">O melhor remédio para o seu bolso!</h2>
<img src="../assets/images/cofrinho-main.jpg">

<div class="savings-calculator" style="padding-top: 10px;">

  <div class="input-group">
    <label for="goal-amount" style="width: 200px;">Quero juntar</label>
    <input type="number" id="goal-amount" placeholder="Digite o valor do seu objetivo" />
  </div>

  <div class="input-group">
    <label for="monthly-saving" style="width: 200px;">Quantia por mês</label>
    <input type="number" id="monthly-saving" placeholder="Digite o quanto você pode guardar por mês" />
  </div>

  <button id="calculate-btn">Calcular</button>


<div class="result" id="resultDiv" style="display: none;">
  <div class="comparison" style="margin-right: 20px; margin-bottom: 20px; width: 100%; max-width: 500px; display: inline-block; vertical-align: top;">
    <h4 style="text-align: center;">Guardando na poupança</h4>
    <p>Você chegará nesse objetivo em <span id="result-months"></span> meses.</p>
    <div class="row">
      <span>6 meses</span>
      <span id="six-months"></span>
    </div>
    <div class="row">
      <span>1 ano</span>
      <span id="one-year"></span>
    </div>
    <div class="row">
      <span>2 anos</span>
      <span id="two-years"></span>
    </div>
    <div class="row">
      <span>5 anos</span>
      <span id="five-years"></span>
    </div>
    <div class="row">
      <span>10 anos</span>
      <span id="ten-years"></span>
    </div>
    <div class="row">
      <span>15 anos</span>
      <span id="fifteen-years"></span>
    </div>
    <div class="row">
      <span>30 anos</span>
      <span id="thirty-years"></span>
    </div>
  </div>
  <div class="comparison" style="margin-bottom: 20px; width: 100%; max-width: 500px; display: inline-block; vertical-align: top;">
    <h4 style="text-align: center;">Investindo com um retorno de 1% ao mês</h4>
    <p>Você chegará nesse objetivo em <span id="result-months-investing"></span> meses.</p>
    <div class="row">
      <span>6 meses</span>
      <span id="six-months-investing"></span>
    </div>
    <div class="row">
      <span>1 ano</span>
      <span id="one-year-investing"></span>
    </div>
    <div class="row">
      <span>2 anos</span>
      <span id="two-years-investing"></span>
    </div>
    <div class="row">
      <span>5 anos</span>
      <span id="five-years-investing"></span>
    </div>
    <div class="row">
      <span>10 anos</span>
      <span id="ten-years-investing"></span>
    </div>
    <div class="row">
      <span>15 anos</span>
      <span id="fifteen-years-investing"></span>
    </div>
    <div class="row">
      <span>30 anos</span>
      <span id="thirty-years-investing"></span>
    </div>
  </div>
</div>


<!-- <div class="result" id="resultDiv" style="display: none; display: flex; flex-wrap: wrap;">
  <div class="comparison" style="flex: 1; max-width: 50%;">
    <h4 style="text-align: center;">Guardando na poupança</h4>
    <p>Você chegará nesse objetivo em <span id="result-months"></span> meses.</p>
    <div class="row">
      <span>6 meses</span>
      <span id="six-months"></span>
    </div>
    <div class="row">
      <span>1 ano</span>
      <span id="one-year"></span>
    </div>
    <div class="row">
      <span>2 anos</span>
      <span id="two-years"></span>
    </div>
    <div class="row">
      <span>5 anos</span>
      <span id="five-years"></span>
    </div>
    <div class="row">
      <span>10 anos</span>
      <span id="ten-years"></span>
    </div>
    <div class="row">
      <span>15 anos</span>
      <span id="fifteen-years"></span>
    </div>
    <div class="row">
      <span>30 anos</span>
      <span id="thirty-years"></span>
    </div>
  </div>
  <div class="comparison" style="flex: 1; max-width: 50%;">
    <h4 style="text-align: center;">Investindo com um retorno de 1% ao mês</h4>
    <p>Você chegará nesse objetivo em <span id="result-months-investing"></span> meses.</p>
    <div class="row">
      <span>6 meses</span>
      <span id="six-months-investing"></span>
    </div>
    <div class="row">
      <span>1 ano</span>
      <span id="one-year-investing"></span>
    </div>
    <div class="row">
      <span>2 anos</span>
      <span id="two-years-investing"></span>
    </div>
    <div class="row">
      <span>5 anos</span>
      <span id="five-years-investing"></span>
    </div>
    <div class="row">
      <span>10 anos</span>
      <span id="ten-years-investing"></span>
    </div>
    <div class="row">
      <span>15 anos</span>
      <span id="fifteen-years-investing"></span>
    </div>
    <div class="row">
      <span>30 anos</span>
      <span id="thirty-years-investing"></span>
    </div>
  </div>
</div> -->


<script>
  const goalAmountInput = document.getElementById('goal-amount');
  const monthlySavingInput = document.getElementById('monthly-saving');
  const calculateBtn = document.getElementById('calculate-btn');
  const resultMonths = document.getElementById('result-months');
  const resultMonthsInvesting = document.getElementById('result-months-investing');

  const sixMonths = document.getElementById('six-months');
  const oneYear = document.getElementById('one-year');
  const twoYears = document.getElementById('two-years');
  const fiveYears = document.getElementById('five-years');
  const tenYears = document.getElementById('ten-years');
  const fifteenYears = document.getElementById('fifteen-years');
  const thirtyYears = document.getElementById('thirty-years');
  
  const sixMonthsInvesting = document.getElementById('six-months-investing');
  const oneYearInvesting = document.getElementById('one-year-investing');
  const twoYearsInvesting = document.getElementById('two-years-investing');
  const fiveYearsInvesting = document.getElementById('five-years-investing');
  const tenYearsInvesting = document.getElementById('ten-years-investing');
  const fifteenYearsInvesting = document.getElementById('fifteen-years-investing');
  const thirtyYearsInvesting = document.getElementById('thirty-years-investing');

  function calculateFutureValue(monthlySavings, months, interestRate = 0.01) {
    return (monthlySavings * ((1 + interestRate) ** months - 1) / interestRate).toFixed(2);
  }

  function calculateFutureValueInvesting(savingsGoal, monthlySavings, interestRate = 0.01) {
    let months = 0;
    let currentSavings = 0;
    while (currentSavings < savingsGoal) {
      currentSavings += monthlySavings * (1 + interestRate) ** months;
      months++;
    }
    return months;
}


  function calculateMonthsToGoal() {
    const goalAmount = Number(goalAmountInput.value);
    const monthlySaving = Number(monthlySavingInput.value);

    // Make sure the inputs are valid numbers
    if (isNaN(goalAmount) || isNaN(monthlySaving)) {
      resultMonths.textContent = '';
      resultMonthsInvesting.textContent = '';
      return;
    }

    // Calculate how many months it will take to reach the goal amount
    const monthsToGoal = Math.ceil(goalAmount / monthlySaving);

    // Update the result element with the calculated value
    resultMonths.textContent = monthsToGoal;
    resultMonthsInvesting.textContent = calculateFutureValueInvesting(goalAmount, monthlySaving);

    // Update the comparison values
    sixMonths.textContent = formatCurrency(monthlySaving * 6);
    oneYear.textContent = formatCurrency(monthlySaving * 12);
    twoYears.textContent = formatCurrency(monthlySaving * 24);
    fiveYears.textContent = formatCurrency(monthlySaving * 60);
    tenYears.textContent = formatCurrency(monthlySaving * 120);
    fifteenYears.textContent = formatCurrency(monthlySaving * 180);
    thirtyYears.textContent = formatCurrency(monthlySaving * 360);

    sixMonthsInvesting.textContent = formatCurrency(calculateFutureValue(monthlySaving, 6));
    oneYearInvesting.textContent = formatCurrency(calculateFutureValue(monthlySaving, 12));
    twoYearsInvesting.textContent = formatCurrency(calculateFutureValue(monthlySaving, 24));
    fiveYearsInvesting.textContent = formatCurrency(calculateFutureValue(monthlySaving, 60));
    tenYearsInvesting.textContent = formatCurrency(calculateFutureValue(monthlySaving, 120));
    fifteenYearsInvesting.textContent = formatCurrency(calculateFutureValue(monthlySaving, 180));
    thirtyYearsInvesting.textContent = formatCurrency(calculateFutureValue(monthlySaving, 360));
  }

  function formatCurrency(amount) {
    return new Intl.NumberFormat('en-US', { style: 'currency', currency: 'USD' }).format(amount);
  }

  // Call the calculateMonthsToGoal function whenever the input values change
  goalAmountInput.addEventListener('input', calculateMonthsToGoal);
  monthlySavingInput.addEventListener('input', calculateMonthsToGoal);

  // Call the calculateMonthsToGoal function when the "Calculate" button is clicked
  // calculateBtn.addEventListener('click', calculateMonthsToGoal);
  calculateBtn.addEventListener('click', function() {
    const resultDiv = document.getElementById('resultDiv');
    resultDiv.style.display = "block";
    // resultDiv.classList.toggle('hidden');
  });

</script>
