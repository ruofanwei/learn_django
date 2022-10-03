### Installation & Setup

- `pip install - pip3 install package_name --user`

##### pip的基本功能 - 安裝套件
- `python3.9 -m pip install --upgrade pip`

##### pip的基本功能就是安裝套件
- `pip3 install virtualenv`
##### 安裝 virtualenv
- `python3 -m virtualenv env` 
##### 進入虛擬環境模式
- `source ./env/bin/activate`

- `pip3 install Django`


### Run project
- `python3 manage.py runserver`

### 🚀 Track recent learning

<details>
<summary>  [Day1 - Views & URL's](https://github.com/ruofanwei/learn_django/tree/Day1_Views_and_URL) </summary>

- By default, the runserver command starts the development server on the internal IP at port 8000
- The development server automatically reloads Python code for each request as needed. You don’t need to restart the server for code changes to take effect.
- [include()](https://docs.djangoproject.com/en/4.1/ref/urls/#django.urls.include) function allows referencing other URLconfs
  - When to use include()
    - should always use include() when you include other URL patterns. admin.site.urls is the only exception to this.
</details>