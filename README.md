Web Project - E-Market

Proje Açıklaması

Bu proje, modern bir e-ticaret platformu olarak geliştirilmiştir. Kullanıcılar ürünleri görüntüleyebilir, sepete ekleyebilir ve sipariş verebilir. Platform, React (Frontend) ve Sanic (Backend) kullanılarak oluşturulmuştur.

Kullanılan Teknolojiler

Frontend: React, Tailwind CSS

Backend: Sanic (Python), Node.js

Veritabanı: PostgreSQL

State Management: Context API

Paket Yönetimi: npm 10.8.2

Diğer: JWT Authentication, RESTful API

Kurulum

Gereksinimler

Node.js 20.18.1 ve üzeri

Python 3.9+ (Sanic için)

PostgreSQL 13+

Adımlar

Depoyu klonlayın:

git clone https://github.com/kullanici/web-project.git
cd web-project

Frontend Kurulumu:

cd frontend
npm install
npm start

Backend Kurulumu:

cd backend
python -m venv venv
source venv/bin/activate  # (Windows için: venv\Scripts\activate)
pip install -r requirements.txt
python app.py

Kullanım

Ana sayfada kategoriler ve ürünler listelenir.

Kullanıcılar ürünleri sepete ekleyebilir ve adetlerini değiştirebilir.

Sepet sayfasında eklenen ürünler görülebilir.

Kullanıcılar giriş yapabilir ve satın alma işlemi gerçekleştirebilir.
