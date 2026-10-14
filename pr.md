# PR

## Deskriptif
1. mulai
2. masukan nilai celcius yang ingin dikonversi
3. menghitung nilai reamur dengan mengalikan nilai celcius dengan hasil 4 dibagi 5, kemudian di cetak dengan menambahkan teks di depanya yaitu Reamur: 
4. menghitung nilai kelvin dengan menambahkan celcius dengan 273.15, kemudian di cetak dengan menambahkan teks di depanya yaitu Kelvin:
5. menghitung nilai fahrenheit dengan mengalikan celcius dengan hasil pembagian 9 dibagi 5, kemudian menjumlahkan dengan 32, terakhir di cetak dengan teks didepanya yaitu  
6. cetak hasil konversi suhu
7. selesai

### Flowchart
```mermaid

flowchart LR
    Start((mulai))
    Celcius[/celcius/]
    HasilReamur[/"#quot;Suhu di Reamur: #quot; + (celcius * (4/5))"/]
    HasilKelvin[/"#quot;Suhu di Kelvin: #quot; + (celcius + 273.15)"/]
    HasilFahrenheit[/"#quot;Suhu di Fahrenheit: #quot; + (celcius * (9/5) + 32)"/]
    End(((selesai)))

    Start --> Celcius
    Celcius --> HasilReamur
    HasilReamur --> HasilKelvin
    HasilKelvin --> HasilFahrenheit
    HasilFahrenheit --> End

```

### Pseudo Code
```
DECLARE celcius : REAL
INPUT celcius
OUTPUT "Reamur: ", (celcius * (4 / 5)) 
OUTPUT "Kelvin: ", (celcius + 273.15)
OUTPUT "Fahrenheit: ", (celcius * (9/5) + 32)
```
