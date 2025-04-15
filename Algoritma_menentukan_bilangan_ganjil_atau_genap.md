1. mulai
2. tentukan angka yang ingin digunakan
3. bagikan angka tersebut dengan 2 
4. jika hasilnya 0 maka itu bilangan genap 
5. jika hasilnya tidak sama dengan 0 maka itu bilangan ganjil
6. tampilkan bilangan genap
7. tampilkan bilangan ganjil
8. selesai

# Flowchart

```mermaid
flowchart TD
    a@{shape: circle, label: "Mulai"}
    b@{shape: lean-r, label: "x"}
    c{x % 2 = 0}
    d[ganjil]
    e[genap]
    x@{shape: dbl-circ, label: "selesai"}

    a --> b
    b --> c
    c -->|False|d
    c -->|True| e
    e --> x
    d --> x
    

    ```