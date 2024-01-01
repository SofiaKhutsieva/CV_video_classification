# CV_video_classification

Задача:  
Необходимо создать модель распознавания действий с вагон-цистерной на эстакаде, которая пошагово отслеживает жизненный цикл вагон-цистерны (въезд на эстакаду, подготовка к сливу, слив, подготовка к отъезду, выезд поезда и т. д.).

Для решения задачи вам предоставлен набор видеороликов, каждый из которых относится к одному из четырех классов:

bridge_down - класс "мостик опущен",  
bridge_up - класс "мостик поднят",   \
no_action - класс "нет операций в кадре",  
train_in_out - класс "въезд/выезд цистерны".

В одном ролике может быть ровно один класс. Особенность задачи заключается в том, что модель распознавания не должна требовать дорогой и долгой дотренировки или сбора дополнительных данных для развертывания системы видеоаналитики в новых локациях. Кроме того, модель должна быть устойчива к потере связи, т. е. пропущенным кадрам в видео.

Метрика - F1 (macro).
