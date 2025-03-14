# 11-3

Параграф 3
1.Сжатие данных без потерь происходит за счёт поиска и устранения статистической избыточности в данных. Алгоритмы анализируют файл, находят повторяющиеся участки или закономерности и заменяют их более короткими представлениями. Такой подход позволяет сократить общий размер файла, не теряя при этом ни одного бита исходной информации.

2.Некоторые типы файлов, которые хорошо сжимаются:
•	файлы документов с расширением DOC или DOCX; 
•	исполняемые файлы (EXE).

3. Если текстовый файл, записанный в однобайтной кодировке, содержит только 33 заглавные русские буквы, цифры и пробел, то:
•	Минимальное число битов на символ при передаче, если каждый символ кодируется одинаковым числом битов, — 6 бит.  
•	Размер заголовка пакета данных — 3 байта.  
•	Минимальная длина текста, при которой коэффициент сжатия будет больше 1, — больше 12 символов.  

4. Алгоритм сжатия RLE (кодирование длин серий) основан на замене повторяющихся символов (серий) на один символ и число его повторов.

5. Префиксный код — код, в котором никакое кодовое слово не является префиксом какого-то другого кодового слова.

6. Сжатие с потерями допустимо в случаях, когда незначительная потеря некоторой информации может быть допустима для достижения более значительного сжатия данных.

7. Простейшие методы сжатия рисунков с потерями:
   - Дельта-модуляция. Алгоритм использует предсказание на основе одного предыдущего пиксела. Точность предсказания определяет степень сжатия и искажения, которые вносятся в сжатое изображение.  
   - Алгоритм JPEG.  Изображение разделяется на один слой яркости и два слоя цвета. Эти слои нарезаются на квадраты 8×8 пикселей и кодируются с помощью особой математики. Если в квадрате есть что-то важное, то оно кодируется и данные сохраняются. Если квадрат более-менее однородный, то он записывается как однородный, данных мало.

8. PEG — Joint Photographic Expert Group — подразделение в рамках ISO — международной организации по стандартизации. В целом алгоритм основан на дискретном косинусном преобразовании (в дальнейшем ДКП), применяемом к матрице изображения для получения некоторой новой матрицы коэффициентов. Для получения исходного изображения применяется обратное преобразование. Для этого используется квантование коэффициентов.

9. Артефакты в программировании — это элементы, которые описывают архитектуру, дизайн и функцию программного обеспечения.

10. JPEG (JOINT PHOTOGRAPHIC EXPERTS GROUP). Метод, используемый для хранения полутоновых и полноцветных изображений, позволяющий добиться лучшей степени сжатия и минимального размера выходного файла. Принцип работы основан на особенностях восприятия человеческим глазом различных цветов. Предназначен для хранения в основном фотографических изображений с большим количеством оттенков и цветовых переходов.

11. Сжатие звука в алгоритме MP3 основано на психоакустической модели звуковосприятия человека.

12. Битрейт — количество бит, используемых для передачи/обработки данных в единицу времени.  Обычно это количество бит, которое приходится на 1 секунду воспроизводимого потока данных (обычно — аудио или видео).

13. На непрофессиональном уровне за эталон качества звука принимают количество килобайтов звукового потока в секунду (Kbps), иначе говоря, битрейт. Также важную роль играет формат звукового файла, или его расширение.

14. Для сжатия видео используются различные методы, среди которых:
•	MotionJPEG или MJPEG. Алгоритм JPEG используется для сжатия не одного, а нескольких кадров.  
•	DV. Обеспечивает лучшее качество при таком же потоке данных. Алгоритм использует гибкую схему компрессии, основанную на адаптивном подборе коэффициента сжатия для различных кадров видео и частей одного кадра. 
•	MPEG. Поскольку видеосигнал транслируется в реальном времени, то нет возможности обработать все кадры одновременно. В алгоритме запоминается несколько кадров. Основной принцип состоит в предположении того, что соседние кадры мало отличаются друг от друга. 
•	Компенсация движения. Позволяет находить похожие участки, даже если они сдвинуты относительно предыдущего кадра.  
•	Дискретное косинусное преобразование (DCT) или его модификации.  Используется для устранения пространственной избыточности. 
•	Фрактальное сжатие и дискретное вейвлет-преобразование. Сейчас обычно применяются только для компрессии неподвижных изображений.
