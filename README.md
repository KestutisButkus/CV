# CV Generatorius su CSV failais

## Kaip naudoti

### 1. Failų struktūra

Kiekvienam CV reikia 7 CSV failų su prefiksu (pvz., `cv1_`):

- `cv1_info.csv` - pagrindinis info (vardas, pareigos, apie)
- `cv1_kontaktai.csv` - kontaktinė informacija
- `cv1_issilavinimas.csv` - išsilavinimas
- `cv1_kalbos.csv` - kalbos
- `cv1_patirtis.csv` - darbo patirtis
- `cv1_igudziai.csv` - įgūdžiai
- `cv1_papildoma.csv` - papildoma informacija

### 2. Kaip redaguoti

**Excel / Google Sheets:**
1. Atidarykite CSV failą Excel'yje arba Google Sheets
2. Redaguokite duomenis
3. Išsaugokite kaip CSV (išlaikant pavadinimą)

**Arba Notepad:**
- Galite redaguoti tiesiog teksto redaktoriumi
- Svarbu išlaikyti kabutes jei tekstas turi kablelių

### 3. Naujo CV pridėjimas

1. Nukopijuokite visus `cv1_*.csv` failus
2. Pervadinkite juos į `cv2_*.csv` (arba `cv3_*.csv`)
3. Redaguokite naujus failus
4. HTML'e jau yra dropdown su CV 1, CV 2, CV 3

### 4. Pavyzdžiai

**cv1_info.csv:**
```
vardas,pareigos,apie
"Jonas Jonaitis","Programuotojas","Aprašymas apie mane..."
```

**cv1_kontaktai.csv:**
```
kontaktas
📧 email@example.lt
📱 +370 600 00000
```

**cv1_issilavinimas.csv:**
```
mokykla,metai,sritis
"Universitetas","2020-2024","Informatika"
```

**cv1_patirtis.csv:**
```
imone,metai,pareigos
"UAB Kompanija","2022-Dabar","Aprašymas darbo..."
```

### 5. Svarbu

- Jei tekstas turi kablelių ar kabučių - įdėkite jį į kabutes
- Excel automatiškai tvarko kabutes
- Tuščias laukas: tiesiog nieko nerašykite tarp kablelių

### 6. PDF generavimas

Spauskite "PDF" mygtuką viršuje - CV bus išsaugotas kaip PDF failas.

## Privalumai

✅ Lengva redaguoti Excel/Google Sheets
✅ Nereikia mokėti JSON
✅ Galima greitai kopijuoti/keitinėti
✅ Aiškesnė struktūra
