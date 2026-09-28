```html
<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Blus>ai</title>

<style>
:root {
    --bg: #eef2ff;
    --card: rgba(255,255,255,.92);
    --text: #172033;
    --muted: #64748b;
    --primary: #4f46e5;
    --primary2: #7c3aed;
    --border: #e2e8f0;
    --shadow: 0 20px 60px rgba(15,23,42,.12);
}

* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: Arial, Helvetica, sans-serif;
    min-height: 100vh;
    background:
        radial-gradient(circle at top left, #c7d2fe, transparent 35%),
        radial-gradient(circle at bottom right, #ddd6fe, transparent 35%),
        var(--bg);
    color: var(--text);
    transition: .3s;
}

body.dark {
    --bg: #0f172a;
    --card: rgba(15,23,42,.94);
    --text: #f8fafc;
    --muted: #94a3b8;
    --border: #334155;
    --shadow: 0 20px 60px rgba(0,0,0,.4);
}

/* HEADER */

.header {
    max-width: 1100px;
    margin: auto;
    padding: 35px 20px 20px;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.brand {
    display: flex;
    align-items: center;
    gap: 14px;
}

.logo {
    width: 58px;
    height: 58px;
    display: grid;
    place-items: center;
    border-radius: 18px;
    background: linear-gradient(135deg,var(--primary),var(--primary2));
    color: white;
    font-size: 30px;
    box-shadow: 0 10px 30px rgba(79,70,229,.35);
}

.brand h1 {
    font-size: 25px;
}

.brand p {
    color: var(--muted);
    margin-top: 4px;
    font-size: 14px;
}

.theme-btn {
    border: 1px solid var(--border);
    background: var(--card);
    color: var(--text);
    width: 45px;
    height: 45px;
    border-radius: 14px;
    cursor: pointer;
    font-size: 20px;
}

/* MAIN */

.container {
    max-width: 1100px;
    margin: auto;
    padding: 10px 20px 40px;
}

.main-card {
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: 28px;
    padding: 30px;
    box-shadow: var(--shadow);
    backdrop-filter: blur(15px);
}

/* INTRO */

.hero {
    margin-bottom: 25px;
}

.hero h2 {
    font-size: 28px;
    margin-bottom: 8px;
}

.hero p {
    color: var(--muted);
    line-height: 1.6;
}

/* TEXTAREA */

.input-title {
    display: flex;
    justify-content: space-between;
    margin-bottom: 10px;
    font-weight: bold;
}

.counter {
    color: var(--muted);
    font-size: 13px;
}

textarea {
    width: 100%;
    min-height: 180px;
    resize: vertical;
    padding: 18px;
    border-radius: 18px;
    border: 2px solid var(--border);
    background: transparent;
    color: var(--text);
    font-size: 16px;
    outline: none;
    transition: .25s;
}

textarea:focus {
    border-color: var(--primary);
    box-shadow: 0 0 0 4px rgba(79,70,229,.12);
}

textarea::placeholder {
    color: #94a3b8;
}

/* BUTTON */

.actions {
    display: grid;
    grid-template-columns: 1fr auto;
    gap: 12px;
    margin-top: 15px;
}

button {
    font-family: inherit;
}

.btn {
    border: none;
    padding: 14px 20px;
    border-radius: 14px;
    font-size: 15px;
    font-weight: bold;
    cursor: pointer;
    transition: .2s;
}

.btn:hover {
    transform: translateY(-2px);
}

.analyze {
    background: linear-gradient(135deg,var(--primary),var(--primary2));
    color: white;
    box-shadow: 0 10px 25px rgba(79,70,229,.3);
}

.reset {
    background: #e2e8f0;
    color: #334155;
}

body.dark .reset {
    background: #334155;
    color: white;
}

/* EXAMPLES */

.examples {
    margin-top: 20px;
}

.examples-title {
    color: var(--muted);
    font-size: 14px;
    margin-bottom: 10px;
}

.example-buttons {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
}

.example {
    padding: 9px 13px;
    border-radius: 12px;
    border: 1px solid var(--border);
    background: transparent;
    color: var(--text);
    cursor: pointer;
}

.example:hover {
    background: rgba(79,70,229,.1);
}

/* RESULT */

#result {
    display: none;
    margin-top: 30px;
    animation: showResult .5s ease;
}

@keyframes showResult {
    from {
        opacity: 0;
        transform: translateY(15px);
    }

    to {
        opacity: 1;
        transform: translateY(0);
    }
}

/* STATUS */

.status {
    padding: 20px;
    border-radius: 18px;
    text-align: center;
    font-weight: bold;
    font-size: 19px;
    margin-bottom: 20px;
}

.status-bad {
    background: #fee2e2;
    color: #991b1b;
}

.status-negative {
    background: #fef3c7;
    color: #92400e;
}

.status-positive {
    background: #dcfce7;
    color: #166534;
}

.status-neutral {
    background: #dbeafe;
    color: #1e40af;
}

/* STATISTICS */

.stats {
    display: grid;
    grid-template-columns: repeat(3,1fr);
    gap: 15px;
}

.stat {
    border-radius: 20px;
    padding: 22px;
    border: 1px solid var(--border);
}

.stat-icon {
    font-size: 25px;
}

.stat-name {
    color: var(--muted);
    margin-top: 8px;
    font-size: 14px;
}

.stat-number {
    font-size: 36px;
    font-weight: bold;
    margin-top: 5px;
}

.stat.bad {
    background: rgba(239,68,68,.1);
}

.stat.negative {
    background: rgba(245,158,11,.1);
}

.stat.positive {
    background: rgba(34,197,94,.1);
}

.bad .stat-number {
    color: #ef4444;
}

.negative .stat-number {
    color: #f59e0b;
}

.positive .stat-number {
    color: #22c55e;
}

/* BOX */

.result-box {
    margin-top: 18px;
    border: 1px solid var(--border);
    border-radius: 20px;
    padding: 22px;
    background: rgba(148,163,184,.06);
}

.box-header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-bottom: 15px;
}

.box-header h3 {
    font-size: 17px;
}

.copy-btn {
    border: 1px solid var(--border);
    background: transparent;
    color: var(--text);
    border-radius: 9px;
    padding: 7px 10px;
    cursor: pointer;
}

/* TAG */

.tags {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
}

.tag {
    padding: 8px 12px;
    border-radius: 30px;
    font-size: 13px;
    font-weight: bold;
}

.tag-bad {
    background: #ef4444;
    color: white;
}

.tag-negative {
    background: #f59e0b;
    color: white;
}

.tag-positive {
    background: #22c55e;
    color: white;
}

/* FILTERED */

.filtered {
    background: #0f172a;
    color: #f8fafc;
    border-radius: 14px;
    padding: 18px;
    line-height: 1.7;
    min-height: 60px;
    word-break: break-word;
}

/* SCORE */

.score-row {
    display: flex;
    justify-content: space-between;
    font-weight: bold;
    margin-bottom: 10px;
}

.score-value {
    color: var(--primary);
}

.progress {
    width: 100%;
    height: 18px;
    border-radius: 20px;
    overflow: hidden;
    background: #e2e8f0;
}

body.dark .progress {
    background: #334155;
}

#progressBar {
    width: 0%;
    height: 100%;
    border-radius: 20px;
    transition: width .7s ease;
}

/* FOOTER */

.footer {
    text-align: center;
    color: var(--muted);
    font-size: 13px;
    margin-top: 22px;
}

.badge {
    display: inline-block;
    margin-top: 8px;
    padding: 6px 10px;
    border-radius: 20px;
    background: rgba(79,70,229,.1);
    color: var(--primary);
}

/* RESPONSIVE */

@media(max-width:700px) {

    .header {
        padding-top: 20px;
    }

    .brand h1 {
        font-size: 20px;
    }

    .brand p {
        font-size: 12px;
    }

    .main-card {
        padding: 20px;
        border-radius: 22px;
    }

    .hero h2 {
        font-size: 23px;
    }

    .stats {
        grid-template-columns: 1fr;
    }

    .actions {
        grid-template-columns: 1fr;
    }

    .reset {
        width: 100%;
    }

}

/* LOADING */

.loading {
    pointer-events: none;
    opacity: .75;
}

.spinner {
    display: inline-block;
    width: 15px;
    height: 15px;
    border: 2px solid rgba(255,255,255,.5);
    border-top-color: white;
    border-radius: 50%;
    animation: spin .7s linear infinite;
    vertical-align: middle;
}

@keyframes spin {
    to {
        transform: rotate(360deg);
    }
}
</style>
</head>

<body>

<header class="header">

    <div class="brand">

        <div class="logo">
            🤖
        </div>

        <div>
            <h1>AI Blus</h1>
            <p>Analisis komentar Indonesia +62</p>
        </div>

    </div>

    <button
        class="theme-btn"
        onclick="toggleTheme()"
        title="Ganti tema">

        🌙

    </button>

</header>


<main class="container">

<div class="main-card">

    <section class="hero">

        <h2>
            Analisis Komentar dengan AI
        </h2>

        <p>
            Masukkan komentar untuk mendeteksi
            kata kasar, kata negatif, dan kata positif.
            Sistem juga mendukung beberapa kosakata Bahasa Sunda.
        </p>

    </section>


    <div class="input-title">

        <span>💬 Tulis komentar</span>

        <span
            class="counter"
            id="counter">
            0 karakter
        </span>

    </div>


    <textarea
        id="comment"
        maxlength="2000"
        placeholder="Contoh: Pelayanannya sangat bagus dan membantu..."></textarea>


    <div class="actions">

        <button
            class="btn analyze"
            id="analyzeBtn"
            onclick="analyzeComment()">

            🤖 Analisis Komentar

        </button>


        <button
            class="btn reset"
            onclick="resetApp()">

            🔄 Reset

        </button>

    </div>


    <div class="examples">

        <div class="examples-title">
            💡 Coba contoh komentar:
        </div>

        <div class="example-buttons">

            <button
                class="example"
                onclick="exampleBad()">

                🔴 Kasar

            </button>

            <button
                class="example"
                onclick="exampleNegative()">

                🟠 Negatif

            </button>

            <button
                class="example"
                onclick="examplePositive()">

                🟢 Positif

            </button>

            <button
                class="example"
                onclick="exampleSunda()">

                🟣 Sunda

            </button>

            <button
                class="example"
                onclick="exampleNeutral()">

                🔵 Netral

            </button>

        </div>

    </div>


    <!-- HASIL -->

    <section id="result">

        <div
            id="status"
            class="status">
        </div>


        <!-- STATISTIK -->

        <div class="stats">

            <div class="stat bad">

                <div class="stat-icon">
                    🔴
                </div>

                <div class="stat-name">
                    Kata Kasar
                </div>

                <div
                    id="badCount"
                    class="stat-number">
                    0
                </div>

            </div>


            <div class="stat negative">

                <div class="stat-icon">
                    🟠
                </div>

                <div class="stat-name">
                    Kata Negatif
                </div>

                <div
                    id="negativeCount"
                    class="stat-number">
                    0
                </div>

            </div>


            <div class="stat positive">

                <div class="stat-icon">
                    🟢
                </div>

                <div class="stat-name">
                    Kata Positif
                </div>

                <div
                    id="positiveCount"
                    class="stat-number">
                    0
                </div>

            </div>

        </div>


        <!-- KATA TERDETEKSI -->

        <div class="result-box">

            <div class="box-header">

                <h3>
                    🔎 Kata Terdeteksi
                </h3>

            </div>

            <div
                id="detectedWords"
                class="tags">
            </div>

        </div>


        <!-- FILTER -->

        <div class="result-box">

            <div class="box-header">

                <h3>
                    🛡️ Hasil Penyaringan
                </h3>

                <button
                    class="copy-btn"
                    onclick="copyFiltered()">

                    📋 Copy

                </button>

            </div>

            <div
                id="filteredText"
                class="filtered">
            </div>

        </div>


        <!-- SCORE -->

        <div class="result-box">

            <div class="box-header">

                <h3>
                    📊 Tingkat Negatif
                </h3>

            </div>

            <div class="score-row">

                <span>
                    Tingkat risiko
                </span>

                <span
                    id="score"
                    class="score-value">
                    0%
                </span>

            </div>

            <div class="progress">

                <div
                    id="progressBar">
                </div>

            </div>

        </div>

    </section>

</div>


<footer class="footer">

    AI Comment Analyzer

    <div class="badge">
        HTML • CSS • JavaScript
    </div>

</footer>

</main>


<script>

/* =====================================================
   DATABASE KATA KASAR
===================================================== */

const badWords = [

    "kontol",
    "memek",
    "ngentot",
    "brengsek",
    "bangsat",
    "bajingan",
    "kampret",
    "keparat",
    "tai",
    "goblok",
    "tolol",
    "bodoh",
    "bego",
    "idiot",
    "anjing",
    "monyet",
    "sialan",
    "babi",
    "itil",
    "dongo",

    /* Sunda */

    "belegug",
    "bedegong",
    "goblog",
    "gelo",
    "kehed",
    "siah",
    "sia mah",
    "sia teh",

    "dasar belegug",
    "dasar bedegong",
    "dasar goblog",

    "belegug pisan",
    "bedegong pisan",

    "sia belegug",
    "sia bedegong",
    "sia goblog",

    "siah belegug",
    "siah bedegong"

];


/* =====================================================
   DATABASE KATA NEGATIF
===================================================== */

const negativeWords = [

    "gak berguna",
    "ga berguna",
    "nggak berguna",
    "tidak berguna",

    "tidak becus",
    "tidak bagus",
    "tidak baik",

    "sangat buruk",
    "buruk",
    "buruk sekali",
    "buruk banget",

    "sangat mengecewakan",
    "mengecewakan",
    "mengecewakan sekali",

    "menyebalkan",
    "menjengkelkan",
    "menjijikkan",

    "benci",

    "payah",
    "payah banget",

    "jelek",
    "jelek banget",

    "gagal",
    "gagal total",

    "sampah",

    "kesal",
    "sangat kesal",

    "kecewa",
    "sangat kecewa",

    "marah",
    "sangat marah",

    "parah",
    "sangat parah",

    "tidak puas",
    "tidak memuaskan",

    "sangat tidak memuaskan",

    "tidak layak",
    "tidak pantas",

    "tidak profesional",
    "tidak kompeten",

    "tidak membantu",
    "tidak ada gunanya",

    "percuma",
    "menyusahkan",
    "merepotkan",
    "merugikan",
    "meresahkan",

    "mengganggu",
    "mengacaukan",

    "bikin kecewa",
    "bikin kesal",
    "bikin marah",
    "bikin jengkel",

    "hasilnya buruk",
    "hasilnya jelek",

    "pelayanan buruk",
    "pelayanan jelek",
    "pelayanan mengecewakan",

    "kualitas buruk",
    "kualitas jelek",

    "produk mengecewakan",

    "tidak sesuai",
    "tidak sesuai harapan",

    "tidak bisa diandalkan",
    "sulit dipercaya",

    "tidak memuaskan sama sekali",

    "benar-benar buruk",
    "benar-benar jelek",

    /* Sunda */

    "teu alus",
    "teu hade",
    "teu hadé",
    "teu pantes",
    "teu bener",
    "teu puguh",
    "teu guna",
    "goreng",
    "goréng",
    "nguciwakeun",
    "matak kesel",
    "matak ambek",
    "matak nyebelin",
    "ngaganggu",
    "teu nyugemakeun"

];


/* =====================================================
   DATABASE KATA POSITIF
===================================================== */

const positiveWords = [

    "baik",
    "sangat baik",
    "baik sekali",

    "bagus",
    "sangat bagus",
    "bagus sekali",

    "mantap",
    "sangat mantap",

    "keren",
    "sangat keren",

    "luar biasa",

    "hebat",
    "sangat hebat",

    "sempurna",
    "sangat sempurna",

    "puas",
    "sangat puas",

    "memuaskan",
    "sangat memuaskan",

    "membantu",
    "sangat membantu",

    "bermanfaat",
    "sangat bermanfaat",

    "berguna",
    "sangat berguna",

    "berkualitas",
    "sangat berkualitas",

    "profesional",
    "sangat profesional",

    "kompeten",

    "terpercaya",
    "dapat dipercaya",
    "dapat diandalkan",

    "mengagumkan",

    "menyenangkan",
    "sangat menyenangkan",

    "menarik",
    "sangat menarik",

    "mudah digunakan",
    "sangat mudah digunakan",

    "sesuai",
    "sesuai harapan",

    "berhasil",

    "sukses",
    "sangat sukses",

    "rekomendasi",
    "direkomendasikan",
    "sangat direkomendasikan",

    "terbaik",

    "pelayanan baik",
    "pelayanan bagus",
    "pelayanan memuaskan",

    "kualitas bagus",
    "kualitas baik",

    "produk bagus",
    "produk berkualitas",

    "hasilnya bagus",
    "hasilnya baik",

    "kerja bagus",
    "kerja baik",

    "terima kasih",

    "selamat",
    "senang",
    "bahagia",
    "bangga",

    "suka",
    "sangat suka",

    /* Sunda */

    "alus",
    "hadé",
    "hade",
    "saé",
    "sae",

    "alus pisan",
    "hadé pisan",
    "hade pisan",

    "saé pisan",
    "sae pisan",

    "bageur",
    "sopan",
    "ramah",
    "mangpaat",
    "ngabantu",
    "pikaresepeun",
    "matak resep",
    "resep pisan"

];


/* =====================================================
   ESCAPE REGEX
===================================================== */

function escapeRegex(text) {

    return text.replace(
        /[.*+?^${}()|[\]\\]/g,
        "\\$&"
    );

}


/* =====================================================
   DETEKSI KATA
===================================================== */

function findWords(text, list) {

    let found = [];

    list.forEach(word => {

        const regex = new RegExp(
            "(^|\\s)" +
            escapeRegex(word) +
            "(?=\\s|$|[.,!?])",
            "gi"
        );

        if (regex.test(text)) {

            found.push(word);

        }

    });

    return found;

}


/* =====================================================
   ANALISIS
===================================================== */

function analyzeComment() {

    const textarea =
        document.getElementById("comment");

    const original =
        textarea.value.trim();

    if (original === "") {

        alert("Masukkan komentar terlebih dahulu!");

        textarea.focus();

        return;

    }


    const button =
        document.getElementById("analyzeBtn");

    button.classList.add("loading");

    button.innerHTML =
        '<span class="spinner"></span> Menganalisis...';


    setTimeout(() => {

        const text =
            original.toLowerCase();


        const bad =
            findWords(text, badWords);

        const negative =
            findWords(text, negativeWords);

        const positive =
            findWords(text, positiveWords);


        /* COUNT */

        document.getElementById("badCount")
            .textContent = bad.length;

        document.getElementById("negativeCount")
            .textContent = negative.length;

        document.getElementById("positiveCount")
            .textContent = positive.length;


        /* STATUS */

        const status =
            document.getElementById("status");

        status.className = "status";


        if (bad.length > 0) {

            status.classList.add("status-bad");

            status.innerHTML =
                "🔴 Komentar Mengandung Kata Kasar";

        }

        else if (negative.length > 0) {

            status.classList.add("status-negative");

            status.innerHTML =
                "🟠 Komentar Negatif Terdeteksi";

        }

        else if (positive.length > 0) {

            status.classList.add("status-positive");

            status.innerHTML =
                "🟢 Komentar Positif";

        }

        else {

            status.classList.add("status-neutral");

            status.innerHTML =
                "🔵 Komentar Netral";

        }


        /* DETECTED WORDS */

        const detected =
            document.getElementById("detectedWords");

        detected.innerHTML = "";


        bad.forEach(word => {

            detected.innerHTML +=
                `<span class="tag tag-bad">
                    🔴 ${word}
                </span>`;

        });


        negative.forEach(word => {

            detected.innerHTML +=
                `<span class="tag tag-negative">
                    🟠 ${word}
                </span>`;

        });


        positive.forEach(word => {

            detected.innerHTML +=
                `<span class="tag tag-positive">
                    🟢 ${word}
                </span>`;

        });


        if (
            bad.length === 0 &&
            negative.length === 0 &&
            positive.length === 0
        ) {

            detected.innerHTML =
                "Tidak ada kata khusus yang terdeteksi.";

        }


        /* FILTER */

        let filtered = original;


        badWords.forEach(word => {

            const regex =
                new RegExp(
                    escapeRegex(word),
                    "gi"
                );

            filtered =
                filtered.replace(
                    regex,
                    "•••"
                );

        });


        document.getElementById("filteredText")
            .textContent = filtered;


        /* SCORE */

        const totalNegative =
            bad.length + negative.length;

        const score =
            Math.min(
                totalNegative * 15,
                100
            );


        document.getElementById("score")
            .textContent =
            score + "%";


        const progress =
            document.getElementById("progressBar");


        progress.style.width =
            score + "%";


        if (score >= 70) {

            progress.style.background =
                "#ef4444";

        }

        else if (score >= 30) {

            progress.style.background =
                "#f59e0b";

        }

        else {

            progress.style.background =
                "#22c55e";

        }


        /* SHOW */

        document.getElementById("result")
            .style.display = "block";


        /* BUTTON */

        button.classList.remove("loading");

        button.innerHTML =
            "🤖 Analisis Komentar";


        document.getElementById("result")
            .scrollIntoView({
                behavior: "smooth",
                block: "start"
            });

    }, 500);

}


/* =====================================================
   CONTOH
===================================================== */

function exampleBad() {

    document.getElementById("comment").value =
        "Kamu goblok dan kontol, kerjaan kamu gak berguna.";

    updateCounter();

    analyzeComment();

}


function exampleNegative() {

    document.getElementById("comment").value =
        "Hasilnya sangat buruk dan sangat mengecewakan, saya merasa kecewa.";

    updateCounter();

    analyzeComment();

}


function examplePositive() {

    document.getElementById("comment").value =
        "Hasilnya sangat bagus, baik, keren, dan sangat membantu.";

    updateCounter();

    analyzeComment();

}


function exampleSunda() {

    document.getElementById("comment").value =
        "Dasar belegug, hasilna teu alus jeung teu hade.";

    updateCounter();

    analyzeComment();

}


function exampleNeutral() {

    document.getElementById("comment").value =
        "Hari ini saya pergi ke kampus dan mengikuti kegiatan perkuliahan.";

    updateCounter();

    analyzeComment();

}


/* =====================================================
   RESET
===================================================== */

function resetApp() {

    document.getElementById("comment")
        .value = "";

    document.getElementById("result")
        .style.display = "none";

    document.getElementById("badCount")
        .textContent = "0";

    document.getElementById("negativeCount")
        .textContent = "0";

    document.getElementById("positiveCount")
        .textContent = "0";

    document.getElementById("score")
        .textContent = "0%";

    document.getElementById("progressBar")
        .style.width = "0%";

    document.getElementById("detectedWords")
        .innerHTML = "";

    document.getElementById("filteredText")
        .textContent = "";

    updateCounter();

}


/* =====================================================
   COPY HASIL
===================================================== */

function copyFiltered() {

    const text =
        document.getElementById("filteredText")
        .textContent;

    if (!text) return;


    navigator.clipboard.writeText(text)
        .then(() => {

            alert("Hasil penyaringan berhasil disalin!");

        });

}


/* =====================================================
   DARK MODE
===================================================== */

function toggleTheme() {

    document.body.classList.toggle("dark");

    const button =
        document.querySelector(".theme-btn");

    if (
        document.body.classList.contains("dark")
    ) {

        button.textContent = "☀️";

    }

    else {

        button.textContent = "🌙";

    }

}


/* =====================================================
   CHARACTER COUNTER
===================================================== */

function updateCounter() {

    const text =
        document.getElementById("comment")
        .value;

    document.getElementById("counter")
        .textContent =
        text.length + " karakter";

}


document.getElementById("comment")
    .addEventListener(
        "input",
        updateCounter
    );


/* =====================================================
   CTRL + ENTER
===================================================== */

document.getElementById("comment")
    .addEventListener(
        "keydown",
        function(event) {

            if (
                event.ctrlKey &&
                event.key === "Enter"
            ) {

                analyzeComment();

            }

        }
    );

</script>

</body>
</html>
```
