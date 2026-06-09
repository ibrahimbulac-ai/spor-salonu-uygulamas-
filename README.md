# 🏋️‍♂️ Spor Salonu Üyelik Sistemi (Gym Membership System)

Bu proje, bir spor salonunun üye kayıtlarını, eğitmen kadrosunu, üyelik paketlerini ve ödeme takibini terminal üzerinden dinamik ve kalıcı bir şekilde yönetmek amacıyla **Python** dilinde geliştirilmiş Nesne Yönelimli Programlama (OOP) tabanlı bir otomasyon sistemidir.

---

## 📌 Proje Mimarisi ve Kod Yapısı (Ne Yaptık?)

Proje, nesne yönelimli programlama prensiplerine uygun olarak mantıksal bölümlere ayrılmıştır. Aşağıda hangi bölümde ne yapıldığı ve hangi mimari kararların alındığı detaylandırılmıştır:

### 🗺️ Sınıf İlişkileri Şeması
```text
      [ Kisi ]  <-- Soyut Sınıf (Abstract Class)
       /    \
      /      \
  [ Uye ]  [ Eğitmen ]  <-- Kalıtım Alan Alt Sınıflar (Inheritance)
    |
 [ Paket ]              <-- Üyeye Atanan Paket Bilgisi
    |
 [ Ödeme ]              <-- Üyenin Finansal Kaydı
