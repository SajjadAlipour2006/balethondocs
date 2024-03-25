---
categories: [Why Balethon]
tags: []
---

<h2 align="right" dir="rtl">بلتون انعطاف‌پذیر است</h2>

<p align="right" dir="rtl">آبجکت ها بخش بزرگی از رابط کاربری بلتون را تشکیل میدهند و مزیت های بسیاری برای کاربرها به وجود می آورند</p>

<p align="right" dir="rtl">برای مثال یک آبجکت مسیج را در نظر بگیریم<br/>
اگر بخواهیم به متن پیام دسترسی پیدا کنیم باید از این کد استفاده کنیم</p>

```python
message.text
```

<p align="right" dir="rtl">اما اگر به جای آبجکت از یک دیکشنری استفاده میکردیم باید به این صورت این کار را انجام میدادیم</p>

```python
message["text"]
```

<p align="right" dir="rtl">مقادیر موجود در آبجکت ها از پیش تعیین شده هستند و برای دسترسی به آن ها کافیست نام آن ها را بعد از یک نقطه بنویسید<br/>
اما مقادیر دیکشنری ها از پیش تعیین شده نیستند و میوانید به هر مقداری که دوست دارید با نوشتن آن بین "ها دسترسی پیدا کنید</p>

<p align="right" dir="rtl">بنابراین یک نگرانی که هنگام استفاده از آبجکت ها وجود دارد این است که ممکن است سرور بله به هر دلیلی یک مقداری بفرستد که جزئی از مقادیر از پیش تعیین شده آن آبجکت نیست<br/>
در آن صورت چطور به آن مقدار دسترسی پیدا کنیم؟</p>

<p align="right" dir="rtl">بلتون برای این مورد یک راه حل آماده کرده<br/>
علاوه بر راه اصلی میتوان مانند یک دیکشنری هم به مقادیر درون آبجکت های بلتون دسترسی پیدا کرد<br/>
برای مثال میتوانید متن پیام را به این شکل هم از آبجکت مسیج بگیرید</p>

```python
message["text"]
```

<p align="right" dir="rtl">و این دقیقا مثل این است که بنویسید</p>

```python
message.text
```

<p align="right" dir="rtl">مقادیر غیر منتظره هم در آبجکت ها ذخیره میشوند<br/>
در هنگام پرینت کردن آبجکت ها هم میتوانید مقادیر غیر منتظره ذخیره شده درون آن ها را مشاهده کنید<br/>
برای دسترسی به آن ها کافیست دقیقا همانطور که از یک دیکشنری استفاده میکنید بنویسید</p>

```python
message["unexpected_value"]
```

<p align="right" dir="rtl">و به آن مقدار غیر منتظره دسترسی پیدا میکنید<br/>
همچنین دقیقا مانند استفاده از یک دیکشنری اگر تلاش به دسترسی به یک مقدار که وجود ندارد بکنید به ارور برخورد میکنید</p>