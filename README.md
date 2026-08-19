# Lo7at Finder 🚗
> بوت تيليجرام لمتابعة مزادات اللوحات السعودية على أبشر
>
> Real-time Telegram bot for Saudi license plate auction monitoring on Absher

<br>

## فكرة المشروع / The Idea

مزادات لوحات السيارات على أبشر تمشي بسرعة — لوحة اهتمامك تنزل وأنت ما دري، أو تنتهي وأنت ما لحقت.

**Lo7at Finder** يراقب المزادات بدالك ويرسل لك إشعار فوري على تيليجرام بمجرد ما ينزل لوحة تطابق اهتمامك.

> Plate auctions on Absher move fast — your target plate lists and closes before you notice.
> Lo7at Finder watches for you and pings you on Telegram the moment a matching plate appears.

<br>

## كيف يشتغل / How It Works

```
أبشر  ──►  Lo7at Engine  ──►  Telegram
Absher      (monitoring)       (alerts)
```

1. البوت يراقب منصة أبشر بشكل مستمر للوحات الجديدة
2. يطابق كل لوحة جديدة مع قوائم المتابعة الخاصة بكل مستخدم
3. عند التطابق يرسل إشعار فوري على تيليجرام

> The bot continuously monitors Absher for new plate listings, matches each one against each user's watchlist, and fires an instant Telegram alert on a match.

<br>

## أنماط البحث / Search Patterns

ممكن تتابع لوحة بأكثر من طريقة:

| المثال | المعنى |
|--------|--------|
| `س ل م 11` | حروف محددة + رقم محدد |
| `س ل م` | حروف محددة + أي رقم |
| `11` | أي حروف + رقم محدد |

<br>

## المميزات / Features

**مجاني / Free**
- متابعة حتى 5 لوحات
- إشعار فوري عند ظهور اللوحة في المزاد 🔔
- تنبيه قبل ساعة من انتهاء المزاد ⏰
- 3 استعلامات يدوية يومياً

**بريميوم ⭐️ / Premium**
- لوحات غير محدودة
- تنبيه قبل 3 ساعات من انتهاء المزاد 🚨
- تنبيه قبل 15 دقيقة من الانتهاء ⏰
- إشعار فوري عند كل ارتفاع في السومة 📈
- إحصائيات تفصيلية لكل لوحة 📊
- استعلام يدوي كل 30 ثانية بلا حدود

**🎁 تجربة مجانية 14 يوم لكل مستخدم جديد — بدون بطاقة بنكية**

<br>

## الأسعار / Pricing

مدفوع عبر Telegram Stars:

| الباقة | السعر |
|--------|-------|
| شهري | 250 ⭐ (~$5) |
| 6 أشهر | 1000 ⭐ (~$20) |

<br>

## جرب الحين / Try it now

👉 [@Lo7atSA_bot](https://t.me/Lo7atSA_bot)

<br>

## التقنيات / Tech Stack

- **Python 3** — core engine
- **Telegram Bot API** — user interface & alerts
- **Linux VPS** — deployed 24/7 via systemd

<br>

---

> 🔒 **Source code is private.** The implementation details and scraping logic are kept confidential to protect the integrity of the service. This repo documents the project concept, features, and behavior only.
>
> Built by [Sulaiman Ahmed](https://iamsulaiman.dev)
