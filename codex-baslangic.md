# Codex başlangıç promptu (PM için)

Deponun kök klasöründe Codex'i açın ve aşağıdaki kutunun içindekini olduğu gibi yapıştırın.
Codex bu turda hiçbir şeyi değiştirmez; projeyi okuyup size sade bir özet verir.

```
Bu depo "date": 4-7 yaş çocuklar için bilişsel tarama uygulaması (Türkçe ürün; monorepo:
shared/ içerik ve puanlama tipleri, backend/ Fastify + Prisma + Postgres, web/ React + Vite).
Ben projenin PM'iyim. İlk görevin projeyi tanımak; bu turda HİÇBİR dosyayı değiştirme,
commit ya da push yapma.

1. Önce şunları sırayla oku:
   - AGENTS.md (proje kuralları; bundan sonra her işte bunlara uy)
   - README.md (özellikle "PM / ikinci geliştirici kurulumu")
   - docs/calisma-notlari.md (Jira, ses, e-posta, veritabanı, stage)
   - docs/dilim-kapanis.md (her iş sonrası izlenecek liste)
   - docs/tasarim/pm-bekleyenler.md (benim kararımı bekleyen konular)
   - docs/tasarim/uyelik-kullanici-yonetimi.md içindeki son 10 numaralı karar (dosyanın sonu)
   - .claude/agents/ klasöründeki rol tanımlarına göz at (ux-designer, panel-designer,
     gorsel-elestirmen, code-reviewer); bunlar senin için talimat dosyasıdır.
2. Kurulumu doğrula: npm install, sonra AGENTS.md'deki test ve tip denetimi komutlarını
   koş (kök ve web ayrı). Sır dosyaları (backend/.env, .env) bende olmayabilir; bu
   durumda neyin çalıştığını, neyin atlandığını söyle.
3. Bana sade Türkçeyle, teknik terim kullanmadan şunları raporla:
   - Uygulama ne yapıyor, çocuk akışı ve yetişkin paneli neler içeriyor (7 bölümün adları)
   - Asla bozulmaması gereken kurallar (en önemli 5-6 tanesi)
   - Bir değişiklik yaptığımızda izleyeceğimiz adımlar, kısaca
   - Benim kararımı bekleyen konuların kısa listesi
   - Kurulumda ve testlerde ne çıktı
4. Bundan sonraki işlerde:
   - main'e doğrudan yazma; her iş için "pm/<konu>" adlı dal aç, bitince PR öner.
   - İşe başlarken ve push'tan önce git pull --rebase yap (ürün sahibi de aynı depoda çalışıyor).
   - work_notes/ klasörüne ve sır dosyalarına dokunma; şapkalı a kullanma.
   - Soru, seçenek, cevap anahtarı, süre ya da puan eşiği değiştirmen gerekirse önce bana sor.
```
