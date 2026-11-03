# Konu: Git ve GitHub Araştırması

## Araştırma

Git: Projelerdeki değişiklikleri adım adım kaydeden, versiyon kontrol sistemidir. Kimin, ne zaman, nerede, hangi kodu değiştirdiğini tutar.

GitHub: Git altyapısını kullanan, projeleri internet üzerinde depolamamızı, paylaşmamızı ve başka yazılımcılarla ortak çalışmamızı (collaboration) sağlayan bulut tabanlı bir platformdur.

Farkı: Git senin bilgisayarında çalışan yerel bir motordur, GitHub ise bu motorla ürettiğin projeleri sergilediğin ve sakladığın online bir vitrindir.

Repository (Repo): Projene ait tüm dosyaların, klasörlerin ve geçmiş değişiklik kayıtlarının tutulduğu ana depo.

Commit: Projede yaptığın değişiklikleri bir not düşerek (açıklama yazarak) sisteme kaydetme işlemi. Bir nevi oyunda "save" almak gibidir.

Branch: Ana projeyi bozmadan, risk almadan yeni özellikler denemek veya eklemek için açılan paralel çalışma dalları.

Merge: Farklı branch'lerde (dallarda) yapılan çalışmaları tek bir dalda (genelde main/master) birleştirme işlemi.

Clone: GitHub'daki bir repository'nin birebir kopyasını kendi bilgisayarına indirme işlemi.

Pull: Uzak sunucudaki (GitHub'daki) en güncel değişiklikleri kendi yerel bilgisayarına çekme işlemi.

Push: Kendi bilgisayarında yaptığın yerel değişiklikleri (commitleri) uzak sunucuya (GitHub'a) yükleme işlemi.

.gitignore: Git'in takip etmesini ve GitHub'a yüklemesini istemediğin gereksiz veya şifre içeren gizli dosyaları belirttiğin özel konfigürasyon dosyası.

## Sektörde Kullanımı
Git ve GitHub; yazılım sektöründe kod kayıplarını önlemek, takım içi görev dağılımı yapmak, kod incelemeleri (code review) gerçekleştirmek ve sürekli entegrasyon (CI/CD) süreçlerini yönetmek için kullanılır. Açık kaynak projelerin geliştirilmesinden şirketlerin kurumsal uygulamalarına kadar her alanda endüstri standardı bir araçtır.

## İncelediğim Projeler

React:

GitHub Adresi: github.com/facebook/react

Dil/Framework: JavaScript, TypeScript

Amacı: Kullanıcı arayüzleri oluşturmak için geliştirilen açık kaynaklı frontend kütüphanesi.

Commit / Contributor: ~16.000+ commit, 1.600+ contributor.

Klasör/README Yapısı: packages/ içinde alt modüller ayrılmış. README'si kurulum, dokümantasyon ve katkıda bulunma (contributing) kurallarını çok net anlatıyor.

VS Code:

GitHub Adresi: github.com/microsoft/vscode

Dil/Framework: TypeScript, Node.js

Amacı: Geliştiriciler için hafif, hızlı ve eklentilerle genişletilebilir bir kod editörü sunmak.

Commit / Contributor: ~150.000+ commit, 6.000+ contributor.

Klasör/README Yapısı: src/ ana kodları, extensions/ eklentileri barındırıyor. README'de lisans, hata bildirimi ve nasıl derleneceği detaylıca verilmiş.

Bootstrap:

GitHub Adresi: github.com/twbs/bootstrap

Dil/Framework: SCSS, JavaScript, HTML

Amacı: Hızlı ve duyarlı (responsive) web tasarımları yapmak için kullanılan frontend araç seti.

Commit / Contributor: ~22.000+ commit, 1.300+ contributor.

Klasör/README Yapısı: scss/ ve js/ klasörleriyle yapılandırılmış. README dosyası CDN linkleri ve hızlı başlangıç rehberiyle direkt kullanıma odaklanmış.

## Yaptığım Uygulama
GitHub üzerinde web-programciligi-3 adlı bir repo açarak içine HTML ve CSS'ten oluşan örnek bir web projesi ekledim. Projede anasayfa, iletişim sayfası ve menü ekleyerek 5 adet anlamlı ("Add homepage", "Add contact page" gibi) commit gerçekleştirdim.

## Karşılaştığım Problemler
İlk başta Push işlemi yaparken "authentication" (yetkilendirme) hatası aldım, Personal Access Token (PAT) oluşturup terminalden girerek bu sorunu çözdüm.

## Öğrendiklerim
Versiyon kontrol sistemlerinin sadece bir kod yedekleme aracı olmadığını, aynı zamanda profesyonel proje yönetiminin kalbi olduğunu öğrendim. Kodları tek bir seferde değil, parça parça commit'lemenin önemini kavradım.

## Kaynaklar

git-scm.com/doc

docs.github.com
