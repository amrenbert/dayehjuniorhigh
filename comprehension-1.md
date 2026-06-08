## Part 3: True or False Quiz

🎒 **Instructions:** Read each sentence carefully. Click **True** or **False** to check your answer!

---

### 1. Anna and Zac are very tired when they arrive at the airport.
<button onclick="checkQ1(true)" style="padding: 6px 12px; background-color: #f0f0f0; border: 1px solid #ccc; border-radius: 4px; cursor: pointer;">True</button>
<button onclick="checkQ1(false)" style="padding: 6px 12px; background-color: #f0f0f0; border: 1px solid #ccc; border-radius: 4px; cursor: pointer;">False</button>
<p id="ans1" style="font-weight: bold; margin-top: 8px; min-height: 20px;"></p>

---

### 2. Zac bought a book about the Taj Mahal at a bookstore.
<button onclick="checkQ2(true)" style="padding: 6px 12px; background-color: #f0f0f0; border: 1px solid #ccc; border-radius: 4px; cursor: pointer;">True</button>
<button onclick="checkQ2(false)" style="padding: 6px 12px; background-color: #f0f0f0; border: 1px solid #ccc; border-radius: 4px; cursor: pointer;">False</button>
<p id="ans2" style="font-weight: bold; margin-top: 8px; min-height: 20px;"></p>

---

### 3. Aunt Lea has never been to the Taj Mahal before.
<button onclick="checkQ3(true)" style="padding: 6px 12px; background-color: #f0f0f0; border: 1px solid #ccc; border-radius: 4px; cursor: pointer;">True</button>
<button onclick="checkQ3(false)" style="padding: 6px 12px; background-color: #f0f0f0; border: 1px solid #ccc; border-radius: 4px; cursor: pointer;">False</button>
<p id="ans3" style="font-weight: bold; margin-top: 8px; min-height: 20px;"></p>

---

### 4. Lea, Anna, and Zac take a train to go see the Taj Mahal.
<button onclick="checkQ4(true)" style="padding: 6px 12px; background-color: #f0f0f0; border: 1px solid #ccc; border-radius: 4px; cursor: pointer;">True</button>
<button onclick="checkQ4(false)" style="padding: 6px 12px; background-color: #f0f0f0; border: 1px solid #ccc; border-radius: 4px; cursor: pointer;">False</button>
<p id="ans4" style="font-weight: bold; margin-top: 8px; min-height: 20px;"></p>

---

### 5. Lassi is a popular drink in India.
<button onclick="checkQ5(true)" style="padding: 6px 12px; background-color: #f0f0f0; border: 1px solid #ccc; border-radius: 4px; cursor: pointer;">True</button>
<button onclick="checkQ5(false)" style="padding: 6px 12px; background-color: #f0f0f0; border: 1px solid #ccc; border-radius: 4px; cursor: pointer;">False</button>
<p id="ans5" style="font-weight: bold; margin-top: 8px; min-height: 20px;"></p>


<script>
function checkQ1(guess) {
  const ans = document.getElementById('ans1');
  if (guess === false) { ans.innerHTML = "🎉 Correct!"; ans.style.color = "green"; }
  else { ans.innerHTML = "❌ Try again!"; ans.style.color = "red"; }
}

function checkQ2(guess) {
  const ans = document.getElementById('ans2');
  if (guess === true) { ans.innerHTML = "🎉 Correct!"; ans.style.color = "green"; }
  else { ans.innerHTML = "❌ Try again!"; ans.style.color = "red"; }
}

function checkQ3(guess) {
  const ans = document.getElementById('ans3');
  if (guess === false) { ans.innerHTML = "🎉 Correct!"; ans.style.color = "green"; }
  else { ans.innerHTML = "❌ Try again!"; ans.style.color = "red"; }
}

function checkQ4(guess) {
  const ans = document.getElementById('ans4');
  if (guess === true) { ans.innerHTML = "🎉 Correct!"; ans.style.color = "green"; }
  else { ans.innerHTML = "❌ Try again!"; ans.style.color = "red"; }
}

function checkQ5(guess) {
  const ans = document.getElementById('ans5');
  if (guess === true) { ans.innerHTML = "🎉 Correct!"; ans.style.color = "green"; }
  else { ans.innerHTML = "❌ Try again!"; ans.style.color = "red"; }
}
</script>
