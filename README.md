Это основная ветка для МДК 08.01 (215) Проектирование и разработка интерфейсов пользователя
<br/>В основном верстаем макеты, поэтому будет удобнее сделать отдельную основную ветку, где нет ничего

Для того, чтобы создать новую ветку, нужно написать в консоли:
<br/>```git status``` узнать в какой ветку мы находимся
<br/>Если вы находитесь не в ``master`` ветке, надо ввести:
<br/>```git checkout master``` перенесёт в ветку ```master```
<br/>После, необходимо прописать:
<br/>```git checkout -b <название ветки>``` создаст (-b) и перенесёт в ветку (checkout) 

Для того, чтобы залить изменения проекта в ветку, нужно:
<br/>```git add .``` возьмёт все изменения проекта
<br/>```git commit -m "Название коммита"``` закоммитит их
<br/>```git push origin <название_ветки>``` запушит (в GitHub) ветку и её содержимое
