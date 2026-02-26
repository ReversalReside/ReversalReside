<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=1000&color=6A5ACD&center=true&vCenter=true&width=435&lines=%2Fdev%2FReversalReside;console.log(%22Hi%22);System32%3E+whoami" alt="Typing SVG" />
</div>

```python
# You can use this code in your IDE.
class ReversalReside:
    def __init__(self):
        self.name = "Егор Мостренов"
        self.nick = "ReversalReside"
        self.age = 17
        self.birthplace = "с.Смоленск, Алтайский край"
        self.stacks = ["Python", "JS", "Java", "Rust", "C++"]
        self.traits = {"выгорание": "быстрое", "софтскилы": "коммуникабельный", "мотивация": "ленивый"}
        self.links = {"portfolio": "https://ReversalReside.code", "tg": "@Vu4erk"}
        
    def code(self, task):
        if self.traits["мотивация"] == "ленивый":
            print(f"{self.nick}: *звуки выгорания на {self.stacks[0]}*")
            return "Потом допишу (никогда)"
        return f"Фигачим {task} на {', '.join(self.stacks[:3])}"

dev = ReversalReside()
print(f"{dev.name}, {dev.age} лет, родился в {dev.birthplace}")
print(f"ТГ: {dev.links['tg']} | Портфолио: {dev.links['portfolio']}")
print(dev.code("бот")) 
```
