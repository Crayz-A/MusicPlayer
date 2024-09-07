# MusicPlayer
همه ما از پخش کننده های موسیقی مانند Windows Media Player یا VLC برای پخش موسیقی در سیستم خود استفاده می کنیم. آیا تا به حال خواسته اید که اگر پاسخ شما مثبت است، پخش کننده موسیقی خود را بسازید، پس با پایتون، می توانید یک پخش کننده موسیقی سفارشی بسازید. در این مقاله نحوه ساخت یک پخش کننده موسیقی ساده و در عین حال کاربردی را با استفاده از دو کتابخانه قدرتمند پایتون مشاهده خواهید کرد: Tkinter و Pygame. Tkinter به ما کمک می کند تا رابط کاربری گرافیکی (GUI) ایجاد کنیم، در حالی که Pygame پخش موسیقی را مدیریت می کند. حتی اگر قبلاً از پایتون استفاده نکرده اید و چیزی در مورد آن نمی دانید، جای نگرانی نیست. همانطور که این مقاله شما را در هر مرحله یک به یک راهنمایی می کند و در پایان، یک پخش کننده موسیقی خواهید داشت که می تواند در لیست پخش آهنگ های مورد علاقه شما بارگیری، پخش، مکث و پیمایش را انجام دهد. بنابراین، بیایید شیرجه بزنیم و شروع به ساختن موسیقی کنیم!

# پخش کننده موسیقی با Tkinter و Pygame در پایتون
در اینجا، برای ایجاد برنامه پخش موسیقی با استفاده از پایتون مراحل زیر را دنبال کنید
#### ایجاد محیط مجازی
با استفاده از دستور زیر محیط مجازی ایجاد کنید
```python -m venv env .\env\Scripts\activate.ps1```
![Music player](https://github.com/PaulleDemon/tkVideoPlayer/blob/master/videoplayer_screenshot.png?raw=True](https://media.geeksforgeeks.org/wp-content/uploads/20240610153735/Project-Structure---Music-Player.png)](https://media.geeksforgeeks.org/wp-content/uploads/20240610153735/Project-Structure---Music-Player.png)

#### کتابخانه های Nesseaccary را نصب کنید
```
    pip install tk
    pip install pygame
    pip install requests
```
![music](https://media.geeksforgeeks.org/wp-content/uploads/20240610154009/Music-Player-with-Tkinter-and-Pygame-in-Python.png)
