# hse_hw1_meth  
# Задание 1

Особенности по сравнению с секвенированием ДНК или РНК?
Обычно количество нуклеотидов   С и G (С=G) , а также A и T (A=T) в ДНК примерно одинаково, хотя, конечно, могут быть небольшие различия в РНК. Однако, здесь мы можем наблюдать, что количество нуклеотидов С гораздо меньше нуклеотидов G. Это происходит из-за влияния бисульфитного секвенирования на ДНК, вследствие чего С сменяется на T, именно поэтому количество С меньше чем G.
# FastQC  
<img width="920" alt="Screenshot 2022-02-20 at 00 31 26" src="https://user-images.githubusercontent.com/30021669/154819765-4be1e7d7-7f8d-4916-933c-84007bdf692a.png">
<img width="994" alt="Screenshot 2022-02-20 at 00 31 40" src="https://user-images.githubusercontent.com/30021669/154819769-8e9cbf1b-c319-4480-96bc-024516690224.png">
<img width="909" alt="Screenshot 2022-02-20 at 00 31 52" src="https://user-images.githubusercontent.com/30021669/154819777-acc56425-d295-4306-b2be-d8845df2b23e.png">
<img width="916" alt="Screenshot 2022-02-20 at 00 33 40" src="https://user-images.githubusercontent.com/30021669/154819824-5bedf1d9-4f12-4646-9ee6-a0155c1e8819.png">
<img width="997" alt="Screenshot 2022-02-20 at 00 33 51" src="https://user-images.githubusercontent.com/30021669/154819830-5faca558-28de-4393-829c-8d4b20f577cb.png">
<img width="1031" alt="Screenshot 2022-02-20 at 00 34 00" src="https://user-images.githubusercontent.com/30021669/154819834-4e2812cc-d4e4-43e8-8a09-7d15745754e2.png">
<img width="983" alt="Screenshot 2022-02-20 at 00 34 09" src="https://user-images.githubusercontent.com/30021669/154819841-31e5e586-9cd8-495e-bea9-c327b6185724.png">
<img width="1183" alt="Screenshot 2022-02-20 at 00 34 21" src="https://user-images.githubusercontent.com/30021669/154819847-c0a516c0-7b0c-4b9d-ab3c-8e4ea7ef15a3.png">

# Задание 2

## Статистика  

<img width="468" alt="Screenshot 2022-02-20 at 00 40 43" src="https://user-images.githubusercontent.com/30021669/154820060-f603bf7c-8c0d-4be0-8866-c7a3637e5efa.png">

## Дедупликация

<img width="423" alt="Screenshot 2022-02-20 at 00 41 41" src="https://user-images.githubusercontent.com/30021669/154820090-f399b8be-6594-4837-8fa8-3f44129bc8a1.png">

## Гистограммы с распределением цитозинов по хромосоме

Судя по графи, можно отметить, частота и процент метилирования цитозинов изменяются в связи с началом той или иной из трех стадий  эмбрионального развития мыши.
Соответвенно:
 • В 8cell  в 50% случаев метилирования не происходит
 • В стадии ICM метилирование происходит еще реже
 • В стадии epiblast - в большей части случаев процент метилирование пначинает резко возрастать.
 
 
<img width="718" alt="Screenshot 2022-02-20 at 00 50 51" src="https://user-images.githubusercontent.com/30021669/154820297-49cc4afa-1da6-4878-8e0c-ac4865a81cb0.png">

<img width="742" alt="Screenshot 2022-02-20 at 00 51 02" src="https://user-images.githubusercontent.com/30021669/154820301-108e7520-c44f-4b07-af5c-f9fd10f89e49.png">

<img width="722" alt="Screenshot 2022-02-20 at 00 51 20" src="https://user-images.githubusercontent.com/30021669/154820309-ea35717a-ee9c-4b1c-8d34-e666a6c116d9.png">

## M-bias  

Отметим изменение в соотношении стадии и процента происходящего процесса метилирования.  При смене 1 стадии второй, этот показатель резко уменьшается, но при переходе из 2 в 3 возрастает. В частности, в 8cell наблюдаем примерно 42% метилирования, во 2 стадии ICM этот показатель немного больше 20%, в epiblast он снова увеличивается.  это происходит из-за дифференцировки тканей, то есть изначально процент метилирования мал, но далее, уже в стадии эпибласт, он сильно возрастает, и уже остается на этом уровне

### 8cell
<img width="1021" alt="Screenshot 2022-02-20 at 01 05 33" src="https://user-images.githubusercontent.com/30021669/154820683-f0ae3886-1215-4c05-972c-c5c11f3a4963.png">

### epiblast
<img width="1091" alt="Screenshot 2022-02-20 at 01 06 48" src="https://user-images.githubusercontent.com/30021669/154820704-0ad493cd-9545-4fd3-a6b4-4e33992c1ec3.png">

### icm

<img width="1046" alt="Screenshot 2022-02-20 at 01 07 18" src="https://user-images.githubusercontent.com/30021669/154820716-f0cc087e-c96d-44af-bfb0-4d2531723933.png">

## Визуализация метилирования и покрытия

Процент метирования и покрытия зависит от стадии эмбрионального развития (8cell, epiblast, icm). Сначала покрытие и метилирование резко уменьшаются на стадии icm, а на стадии epiblast увеличиваются.

![image_cov2](https://user-images.githubusercontent.com/30021669/154820760-ab50de93-9f46-4f6d-aa6f-4d72d1df0ad4.png)

![image_cov](https://user-images.githubusercontent.com/30021669/154820763-2f8e2886-6551-4e2e-824d-9f47be59f690.png)


