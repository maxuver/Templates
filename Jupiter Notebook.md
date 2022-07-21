1. **_Создание виртуальной среды для Jupyter:_**

`sudo -H pip3 install --upgrade pip
sudo -H pip3 install virtualenv

Флаг -H устанавливает в переменной среды home домашний каталог целевого пользователя.

2. **_Создание отдельного каталога для файлов проекта и перейдите в него:_**

`mkdir ~/my_project_dir
cd ~/my_project_dir`

3. **_В этом каталоге создайте виртуальную среду Python:_**

`virtualenv my_project_env`

4. **_Активировать виртуальную среду:_**

`source my_project_env/bin/activate`

5. **_Запуск Jupyter Notebook_**

`jupyter notebook`

в конце лога будет ссылка. Перейти по ней или открыть в браузере

**_Сменить тему в Jupyter Notebook:_**

`jt -l
jt -t <new_thema> -T -N -kl`

Перезапустить