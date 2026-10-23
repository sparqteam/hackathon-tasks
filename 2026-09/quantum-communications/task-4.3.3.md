Постройте цепочку, реализующую $\hat{U}_{PCQCM}$ в Qiskit.

Схему необходимо собрать в Qiskit и сдать в формате OpenQASM 3. Для этого после построения схемы `qc` выполните:

```python
from qiskit import qasm3

answer = qasm3.dumps(qc)
answer_line = answer.replace("\n", "\\n")

print(answer_line)
```

В поле ответа вставьте строку, выведенную командой `print(answer_line)`.

Схема должна содержать только операции, относящиеся к решению данной подзадачи.
Подробнее о формате ответа: https://disk.yandex.ru/d/HdAo_WcUpMouPQ

Приложите файл полного решения в печатном формате (PDF, word) к ответу
