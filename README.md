В этом задании я написал поисковый сервер и покрыл его unit тестами на 86%.
Клиент делает запрос на сервер, сервер обрабатывает его, идет в хранилище(по условию задачи данные хранятся в xml и представляют собой список пользователей с характеристиками)
парсит внутренности, далее преобразует данные в соответствии с запросом клиента(сколько юзеров, поисковой запрос, как отсортировать и т.д.) и отправляет клиенту.
Подробные условия вы можете посмотреть в файле hw3.md