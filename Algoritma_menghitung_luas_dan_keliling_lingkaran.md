# Menghitung Luas dan Keliling Lingkaran
1. mulai
2. pertama tama kita hitung luas lingkaran terlebih dahulu
3. dengan menggunakan rumus luas lingkaran = phi x r x r
4. phi = 22/7 atau 3,14
5. r = jari jari lingkaran
6. kalikan angka angka tersebut seperti rumus yang ada
7. tampilkan hasilnya
8. selanjutnya kita hitung keliling lingkaran
9. dengan menggunakan rumus keliling lingkaran = 2 x phi x r
10. 2 = adalah rumus keliling lingkaran
11. phi = 22/7 atau 3,14
12. r = jari jari lingkaran
13. kalikan angka angka tersebut sesuai rumus yang ada
14. tampilkan hasilnya
15. selesai

# Flowchart
```mermaid
flowchart TD
    a@{shape: circle, label: "Mulai"}
    b@{shape: lean-r, label: "input Phi = 22/7 atau 3,14"}
    c{ r }
    d[k = 2 x phi x r]
    e[L = phi x r x r]
    f[/output K dan L/]
    x@{shape: dbl-circ, label: "selesai"}

    a --> b
    b --> c
    c ---->|Keliling| d
    c ---->|Luas| e
    e ----> f
    d ----> f
    f --> x

``` 

# Pseudocode
```
// Lingkaran
DECLARE r: REAL
DECLARE Phi: REAL
DECLARE Luas: REAL
DECLARE Keliling: REAL

SET Phi:3.14

INPUT r

SET Luas= Phi * r * r
SET keliling= 2 * Phi * r

OUTPUT "Luas Lingkaran adalah: ", Luas
OUTPUT "Keliling Lingkaran adalah: ", Keliling

```