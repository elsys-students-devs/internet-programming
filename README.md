# Internet-Programming

## Как да обновите вашето assignment repository

 1. Проверете, че се намирате в папката на вашето repository:

```bash
   cd my-assignment-repo
```
 2. Проверете дали вече имате добавен upstream:
```bash
git remote -v
```
  3. Ако upstream не е в списъка, добавете го (само веднъж):
```bash
   git remote add upstream https://github.com/tvuchova/internet-programming.git
 ``` 
 4.Взимане на последни промени от шаблонa и merge с вашите repository
```bash
   git fetch upstream
   git merge upstream/main
 ``` 

  5. Качете обновеното репо:
 ```bash
   git push origin main
 ``` 

origin – това е вашето копие (fork) на repository-то в GitHub. Когато правите git push origin main, качвате промените в собственото ви репо.

upstream – това е оригиналното repository (в случая: на преподавателя). Когато правите git fetch upstream, взимате последните промени оттам.

