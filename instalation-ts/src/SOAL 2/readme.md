## Kode

```typescript
function printTriangle(height: number): void {
    for (let i = 0; i < height; i++) {
        console.log('*'.repeat(i + 1));
    }
}

printTriangle(7);


## Penjelasan

- **function printTriangle(height: number): void**  
  Mendeklarasikan sebuah fungsi bernama `printTriangle` yang menerima satu parameter `height` bertipe `number` dan tidak mengembalikan nilai (`void`).

- **height**  
  Parameter yang menentukan tinggi dari segitiga yang akan dicetak.

- **Loop for**  
  Dimulai dengan `let i = 0`, yang berarti iterasi pertama dari loop akan dimulai dengan `i` setara dengan 0. Loop akan terus berlanjut selama `i < height`. Dalam contoh ini, `height` adalah 7, jadi loop akan berlanjut sampai `i` mencapai 6 (karena loop akan berhenti ketika `i` mencapai atau melebihi nilai `height`). Setiap iterasi loop, `i` akan bertambah satu (`i++`).

- **console.log('*'.repeat(i + 1))**  
  Perintah untuk mencetak baris pada konsol. `' * '.repeat(i + 1)` menghasilkan string yang terdiri dari karakter bintang (`*`) yang diulang sebanyak `i + 1` kali. 
  - Misalnya, jika `i` adalah 0, `' * '.repeat(1)` menghasilkan satu bintang: `*`.
  - Jika `i` adalah 1, `' * '.repeat(2)` menghasilkan dua bintang: `**`.
  - Proses ini berlanjut dengan menambahkan satu bintang pada setiap baris berikutnya sesuai dengan nilai `i`.

- **printTriangle(7)**  
  Memanggil fungsi `printTriangle` dengan argumen 7. Ini berarti fungsi akan mencetak segitiga dengan tinggi 7 baris, dengan setiap baris bertambah satu bintang dari baris sebelumnya.
