## UNITY ML AGENTS TEST LEVELS

Этот репозиторий предоставляет набор сред сделанных с помощью [Unity ML Agents](https://unity-technologies.github.io/ml-agents/), пригодных для Meta Reinforsment Learning.

[Unity ML Agents](https://unity-technologies.github.io/ml-agents/) - универсальный инструмент  позволяющий создавать среды на движке Unity и предоставляющий удобный интерфейс взаимодействия с Python. Однако на данный момент, существует острая нехватка сред для мета обучения с подкреплением, доступных в открытом домтупе.
По этой причине я решил выложить свои наработки в открытый доступ. 

# Формат возращаемыых данных

Состояние среды описывается 3 компонентами: локальное окружение, карта целей и численными данными. Поговорим о них детально:
Локальное окружение - детальное изображение всех объктов вокруг агента. 
![screenshot](screenshot.png)
