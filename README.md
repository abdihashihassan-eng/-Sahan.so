# 🌟 SAHAN.SO

**SAHAN.SO** waa platform web ah oo aad ku iibsan karto data packages & airtime, kana qayb qaadan karto tartamo, abaalmarino, iyo commission iyadoo la adeegsanayo referral link iyo promo code.

## ✨ Waxyaabaha ugu muhiimsan

- **Iibka Data & Airtime** – 5 tallaabo: shirkadda, adeegga, qorshaha, habka bixinta, iyo xaqiijinta USSD auto-dial.
- **Referral & Promo Codes** – user kasta wuxuu helayaa referral code gaar ah iyo promo code (taxane).
- **Tartamo & Abaalmarino**  
  - Toddobaadle: 5ka qof ee ugu badan soo jiiday  
  - Bille: 5ka iibiyaha ugu sarreeya & 5ka promo code ugu badan la adeegsaday  
  - Sanadle: 5ka degmo, koox, iyo iskuul ee ugu iibka badan  
- **Leaderboard toos ah** – filter, progress bars, glassmorphism.
- **Dashboard** – warbixin ku saabsan referrals, bonus points, promo code, group code.
- **Admin panel** – maareynta products iyo orders (kaliya is_admin=true).
- **Login laba hab** – email/password ama promo code/password.
- **Mobile-friendly** – wuxuu u shaqeeyaa taleefanka, kombuyuutarka, iyo qalabka kale.

## 🛠️ Tiknoolajiyada

| Qayb       | Tiknoolaji                 |
|------------|----------------------------|
| Frontend   | HTML5, CSS3, JavaScript    |
| Backend    | Supabase (PostgreSQL)      |
| Authentication | Supabase Auth          |
| Hosting    | GitHub Pages               |

## 📁 Qaab dhismeedka Database (soo koobid)

- `customers` – macluumaadka isticmaale (referral, promo, district, group, school, bonus points)
- `products` – data packages iyo airtime
- `orders` – iibka la sameeyay, promo code la adeegsaday, receiver phone
- `transactions` – qaybinta tartamada (buyer, district, group, school, referral, promo)
- `rewards` – guuleystayaasha rasmiga ah

## 🔧 Hawlaha RPC ee muhiimka ah

- `register_customer` – isdiiwaangelin oo otomaatig ah
- `create_order` – iib cusub oo leh USSD code
- `get_weekly_top_referrers` – 5ka qof ee ugu badan soo jiiday usbuuca
- `get_monthly_top_promoted` – 5ka qof ee promo code-kooda inta ugu badan la adeegsaday bisha
- `get_top_districts` / `get_top_groups` / `get_top_schools` – tartamada sanadlaha

## 🧪 Sida loo isticmaalo

1. **Ka koobi repository-ga**  
   ```bash
   git clone https://github.com/your-username/Sahan.so.git
