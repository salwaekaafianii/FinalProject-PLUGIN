```
let lirikLagu: {
    status: boolean;
    data: {
        artist: string;
        songTitle: string;
        songLyrics: string;
        songLyricsArr: string[];
    };
} = {
    status: true,
    data: {
        artist: "Avenged Sevenfold",
        songTitle: "Little Piece of Heaven",
        songLyrics: "Before the story begins, is it such a sin\nFor me to take what's mine, until the end of time?\nWe were more than friends, before the story ends\nAnd I will take what's mine, create what God would never design\nOur love had been so strong for far too long",
        songLyricsArr: [
            "Before the story begins, is it such a sin",
            "For me to take what's mine, until the end of time?",
            "We were more than friends, before the story ends",
            "And I will take what's mine, create what God would never design",
            "Our love had been so strong for far too long",
            // (lirik selanjutnya)
        ]
    }
};


    - lirikLagu : variabel bertipe objek yang memiliki dua properti: status dan data. 
    - status : tipe boolean yang menunjukkan apakah data lirik lagu valid atau tidak. 
    - data : objek yang memuat informasi mengenai lagu, dengan properti: 
        - artist (string): Nama artis. 
        - songTitle (string): Judul lagu. 
        - songLyrics (string): Lirik lagu dalam format string. 
        - songLyricsArr (array of string): Lirik lagu dalam bentuk array, setiap elemen adalah baris lirik.
 
## SOAL 2A

