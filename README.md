echo "# shopee-craper" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/buitronghieu2905/shopee-craper.git
git push -u origin main

- Edit `config.yaml` file according to usage

    Example :

    ```yaml
    max-page: 10
    data-per-page: 50
    full-url: 'https://shopee.vn/B%E1%BB%99-%C4%91%C3%B4i-Lotion-v%C3%A0-Serum-d%C6%B0%E1%BB%A1ng-tr%E1%BA%AFng-Senka-(200ml-35g)-i.27495213.2178702737'
    webdriver-path: path/to/web/driver
    file-store-location: data/
    ```

## Usage

```sh
python3 scrap.py
```
