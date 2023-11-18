# Paradigms With Scala Language

## Imperative
* "A função do computador é seguir minhas instruções"
* **mutable** states
* quando o código é chamado mais de 100000x (não exatamente esse número!) o "jit" compila ele, externamente o código tem o mesmo comportamento, porém internamente o jit pode mudar o seu código.
* seu código não esta sendo executado em somente um lugar (concurrent execution). *Concurrent modifications* podem perders dados se você não utilizada uma estrutura "thread-safe".
* Several issues
* *Declarative programming* is when you say what you want, and *imperative* is when you say how to get what you want.
* Degree of abstraction:

``Declarative <<=====|==================>> Imperative``