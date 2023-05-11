# Training 00 - Установка "дистрибутива" python c использованием установщика conda

Скачайте установщик conda c https://docs.conda.io/en/latest/miniconda.html

## Порядок действий

1. Скачать файл environment.yaml в корне данного репозитария на свою машину;
2. Открыть раздел предустановленного дистрибутива anaconda/conda в меню "Пуск" и выбрать пункт "... conda promt..." (для пользователей wind'ы); (стр. 3 short_manual.pdf)
3. В открывшемся терминале выполнить команду conda env create -f "Путь к файлу environment.yaml".

## Или

1. Открыть раздел предустановленного дистрибутива anaconda/conda в меню "Пуск" и выбрать пункт "... conda promt..." (для пользователей wind'ы); (стр. 3 short_manual.pdf)
2. Выполнить команду 
conda create -n ocean python=3.9 numpy scipy pandas xarray matplotlib cartopy netcdf4 jupyterlab spyder -c conda-forge

## Или

Cмотреть старую (немного адаптированную) инструкцию