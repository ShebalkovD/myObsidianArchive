*теги*: #react 
___
# Создание html разметки на JavaScript

Эта библиотека упрощает жизнь разработчику, т.к. использует синтаксис ==jsx==, который упрощает процесс создания html разметки на языке JavaScript. 

Если на JS создание разметки выглядит так:

```JavaScript
function addElement() {
  // Создаём новый элемент div
  // и добавляем в него немного контента

  var newDiv = document.createElement("div");
  newDiv.innerHTML = "<h1>Привет!</h1>";
  newDiv.classList.add("container")
  
  // Добавляем только что созданный элемент в дерево DOM
  my_div = document.getElementById("org_div1");
  document.body.insertBefore(newDiv, my_div);
}
```

Тогда на JSX:

```JSX
function Component() {
	return(
		<div className = "container">
			Привет!
		</div>
	)
}
```







___
# Ссылки