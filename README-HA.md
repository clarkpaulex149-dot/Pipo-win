# PIPO WIN — Gid pou mete sou entènèt ak telefòn

Ou pa bezwen òdinatè pou itilize pwojè a, men ou bezwen yon sèvis hosting ki ka kouri Node.js ak yon PostgreSQL database.

## 1) Prepare database
Kreye yon PostgreSQL database sou yon sèvis tankou Neon, Supabase oswa yon lòt PostgreSQL provider. Kopi DATABASE_URL la.

## 2) Prepare hosting
Kreye yon Web Service Node.js sou yon hosting ki sipòte GitHub/Node.js. Upload pwojè sa a sou GitHub depi telefòn ou, oswa konekte repository a dirèkteman si hosting lan pèmèt sa.

Build command:
npm install

Start command:
npm start

## 3) Environment variables
Sou hosting lan mete:
ADMIN_EMAIL = email pa w
ADMIN_PASSWORD = yon modpas long, inik
SESSION_SECRET = yon string long o aza
DATABASE_URL = PostgreSQL connection string ou

Pa mete .env sou GitHub.

## 4) Admin
Apre deployment:
https://ADRES-SIT-LA/admin

Se sèlman kont ki gen role admin nan database/server lan ki kapab antre.
Registration piblik la toujou kreye role=user; itilizatè pa kapab chwazi role admin.

## 5) Remak
Pwojè a se yon prize-draw demo. Si w ap fè moun peye pou antre oswa gen lajan/lotri, verifye lwa ak lisans ki aplikab anvan w lanse sa piblikman.
