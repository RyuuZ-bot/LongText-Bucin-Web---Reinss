# LongText-Bucin-Web---Reinss
Program dengan beberapa gabungan bahasa pemograman yang dapat meng-generate long text bucin buat gebetan kamu

<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Long Bucin Generator</title>

    <style>
        body {
            margin: 0;
            font-family: "Poppins", sans-serif;
            background: linear-gradient(135deg, #f6d1d1, #ffd6e0);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }

        .container {
            max-width: 600px;
            background: white;
            padding: 30px;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            text-align: center;
        }

        h2 {
            color: #ff5c7c;
            margin-bottom: 10px;
        }

        p {
            color: #444;
            margin-bottom: 20px;
        }

        button {
            background: #ff6b81;
            border: none;
            padding: 12px 20px;
            border-radius: 10px;
            color: white;
            cursor: pointer;
            font-size: 16px;
            transition: 0.2s;
        }

        button:hover {
            background: #ff4757;
        }

        .result {
            margin-top: 25px;
            font-size: 17px;
            font-weight: 500;
            color: #333;
            text-align: left;
            line-height: 1.6;
            white-space: pre-line;
            border-top: 2px solid #ffd0d5;
            padding-top: 20px;
        }
    </style>

</head>
<body>

<div class="container">
    <h2>Long Text Bucin By Reinss</h2>
    <p>Klik tombol untuk membuat paragraf bucin panjang otomatis</p>

    <button onclick="generateLongBucin()">Generate Bucin Panjang</button>

    <div class="result" id="result"></div>
</div>


<script>
    const longBucinTexts = [
        `Aku nggak tau sejak kapan kamu jadi rumah buat semua capekku. Tapi tiap kali aku mikir tentang kamu, semuanya tuh kerasa lebih ringan. Seakan dunia ini nggak seberisik itu. Kamu tuh aneh… kamu masuk ke hidup aku pelan-pelan, tapi pengaruhnya gede banget. Kadang aku takut, takut kalau suatu hari kamu bosen, atau kamu pergi tanpa alasan. Tapi aku tetep di sini, tetap milih kamu, tetap sayang sama kamu. Sesimpel itu. Dan kalau ada satu hal yang aku pengen kamu percaya… itu adalah: aku nggak main-main sama perasaan ini.`,

        `Kamu tau nggak? Dalam hidupku yang berantakan banget ini, kamu satu-satunya hal yang bikin semuanya terasa masuk akal. Aku nggak selalu bisa ngomong langsung, tapi aku mikir tentang kamu lebih sering daripada yang kamu bayangin. Aku kangen kamu bahkan pas kita baru selesai ngobrol. Aku takut kehilangan kamu bahkan pas kamu bilang kamu nggak akan kemana-mana. Gimana sih kamu bisa bikin aku selama itu mikirin kamu? Aku kesel. Tapi aku juga seneng. Karena cuma kamu yang bisa bikin aku kayak gini.`,

        `Ada banyak hal yang nggak bisa aku jelasin dengan kata-kata… tapi perasaan aku ke kamu, itu jelas. Kamu jadi alasan kenapa aku bangun pagi dengan perasaan yang lebih hangat. Kamu jadi alasan kenapa aku ngerasa hidup ini pantas dijalanin. Kamu bikin aku ngerasa dicariin, diperhatiin, dimengerti. Dan aku cuma mau kamu tau satu hal: kalau suatu hari dunia bikin kamu jatuh, aku yang pertama bakal berdiri di depan kamu. Karena sesayang itu aku sama kamu, sebegitunya aku nggak mau kamu terluka sendirian.`,

        `Aku mungkin bukan orang paling romantis, tapi setiap detail tentang kamu ketempel terus di otakku. Cara kamu ketawa, cara kamu marah, cara kamu bales chat, semuanya nyisa. Kadang aku cuma diem dan mikir, “Gimana kalau aku nggak ketemu kamu?”. Mungkin hidupku bakal tetap jalan… tapi pasti nggak akan sehangat sekarang. Kamu itu bukan cuma seseorang yang aku suka. Kamu itu seseorang yang aku pilih. Dengan sadar. Dengan hati penuh. Dengan rasa yang nggak mau aku bagi ke siapa pun selain kamu.`,

        `Kalau suatu hari kamu tanya: “Kenapa kamu sayang sama aku?”… aku mungkin bakal diem dulu. Bukan karena aku nggak punya alasan. Tapi karena ada terlalu banyak. Kamu itu kayak sesuatu yang nggak pernah aku cari, tapi malah jadi hal yang paling aku butuhin. Kamu yang bikin aku mau jadi lebih baik, bukan karena aku kurang, tapi karena aku mau pantas di samping kamu. Dan kalau aku boleh jujur… aku tuh nggak butuh banyak hal di dunia ini. Aku cuma butuh kamu, tetap di sini, tetap jadi tempat aku pulang.`
    ];

    function generateLongBucin() {
        const random = Math.floor(Math.random() * longBucinTexts.length);
        document.getElementById("result").innerText = longBucinTexts[random];
    }
</script>

</body>
</html>
