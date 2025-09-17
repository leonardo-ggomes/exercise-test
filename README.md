### Exercício 1: Depósito simples
Verifique se, ao depositar **100** em uma conta com saldo inicial **0**, o saldo final é **100**.  
👉 Usar `toBe`.

---

### Exercício 2: Saque simples
Teste se, ao sacar **50** de uma conta com saldo **200**, o saldo final é **150**.  
👉 Usar `toBe`.

---

### Exercício 3: Transferência entre contas
Simule a transferência de **100** de uma conta com **500** para outra com **200**.  
Verifique se o saldo da primeira fica **400** e o da segunda fica **300**.  
👉 Usar `toBe`.

---

### Exercício 4: Saldo maior que um valor
Verifique se, após depositar **1000** em uma conta, o saldo fica **maior que 500**.  
👉 Usar `toBeGreaterThan`.

---

### Exercício 5: Saldo mínimo exigido
Teste se, após uma operação, o saldo da conta é **maior ou igual a 50** (saldo mínimo exigido).  
👉 Usar `toBeGreaterThanOrEqual`.

---

### Exercício 6: Conta no limite
Verifique se, após sacar quase todo o dinheiro, o saldo fica **menor que 10**.  
👉 Usar `toBeLessThan`.

---

### Exercício 7: Conta zerada
Simule uma operação onde o cliente retira exatamente o valor que tinha (saldo = 300, saque = 300).  
Verifique se o saldo final é **menor ou igual a 0**.  
👉 Usar `toBeLessThanOrEqual`.

---

### Exercício 8: Correção de arredondamento em juros
Se uma conta rende juros de **0.1 + 0.2**, verifique se o resultado está **próximo de 0.3**.  
👉 Usar `toBeCloseTo`.

---

### Exercício 9: Saldo negativo proibido
Tente simular um saque maior que o saldo (ex.: saldo 100, saque 150).  
Verifique se o resultado final é **menor que 0**.  
👉 Usar `toBeLessThan`.
