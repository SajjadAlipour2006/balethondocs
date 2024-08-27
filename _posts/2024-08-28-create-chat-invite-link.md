---
categories: [Client]
tags: []
---

<h1>Client.<strong>create_chat_invite_link()</strong></h1>

<p align="left" dir="rtl"><strong>ساختن لینک دعوت جدید برای یک چت</strong></p>

<h2>Parameters</h2>

<ul>
<li><strong>chat_id (<a href="https://docs.python.org/3/library/functions.html#int">int</a> | <a href="https://docs.python.org/3/library/stdtypes.html#str">str</a>)</strong><blockquote dir="rtl">
<p><strong>آیدی چتی که لینک دعوت جدید برای آن ساخته میشود</strong></p>
</blockquote>
</li>
</ul>

<h2>Returns</h2>

<blockquote>
<p><code>InviteLink</code></p>
</blockquote>

<h2>Example</h2>

```python
await bot.create_chat_invite_link(1234567890)
```