**1. Clone wallet sources**

```
git clone https://github.com/humanitarycoin/guiwallet.git
```

**2. Modify `CryptoNoteWallet.cmake`**
 
```
set(CN_PROJECT_NAME "humanitarycoin")
set(CN_CURRENCY_DISPLAY_NAME "HumanitaryCoin")
set(CN_CURRENCY_TICKER "HCN")
```

**3. Clone HumanitaryCoin Source in guiwallet past**

```
https://github.com/humanitarycoin/hcn.git
```

Replace URL with git remote repository of your coin.

**4. Build**

```
mkdir build && cd build && cmake .. && make
```
