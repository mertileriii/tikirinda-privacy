# Tıkırında Gizlilik Politikası

Bu depo, Tıkırında uygulamasının gizlilik politikası sayfasını barındırır.

## GitHub Pages Kurulumu

1. Bu klasörü GitHub'da yeni bir **public** repo olarak oluştur: `tikirinda-privacy` (veya istediğin isim)

2. Repo oluşturduktan sonra:
   - **Settings** → **Pages**
   - **Source:** Deploy from a branch
   - **Branch:** main → / (root)
   - **Save**

3. Birkaç dakika sonra sayfa yayında olacak. URL:
   ```
   https://mertileriii.github.io/tikirinda-privacy/
   ```

4. Bu URL'yi App Store Connect → App Information → Privacy Policy URL alanına yapıştır.

## Terminal ile Yükleme

```bash
cd tikirinda-privacy
git init
git add .
git commit -m "Gizlilik politikası"
git branch -M main
git remote add origin https://github.com/mertileriii/tikirinda-privacy.git
git push -u origin main
```
