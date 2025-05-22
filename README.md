### 🎯 Fokus Utama:

* Banyak bug eksploitabel adalah **bug fungsional** yang **tidak bisa dideteksi oleh oracle sederhana** seperti reentrancy.
* Proyek ini mendorong pengembangan **oracle semantik otomatis** yang lebih canggih.

---

## 🗂 Struktur Dataset

* `papers/`: Paper ICSE23 dan materi tambahan.
* `results/`: File bug (`bugs.csv`) dan deskripsi kontes (`contests.csv`).
* `contracts/`: Kode smart contract sesuai versi saat kontes.
* `reports/`: Laporan dari code4rena.

---

## 🏷️ Kategori Bug:

* **O** – Out-of-scope
* **L** – Bisa dideteksi oleh oracle sederhana
* **S** – Butuh oracle semantik lanjutan

---

## 🛠️ Tools & Teknik yang Direkomendasikan

### 🔍 Semantical Oracle Techniques:

| Teknik                | Kategori Bug   |
| --------------------- | -------------- |
| Role Mining           | Access Control |
| AChecker              | Access Control |
| Fairness Verification | Fairness       |
| Clockwork Finance     | TBD            |

### 🧪 Public Security Tools:

| Tool           | Developer           | Fitur                    |
| -------------- | ------------------- | ------------------------ |
| **Slither**    | Trail of Bits       | Analisis statik          |
| **Foundry**    | Paradigm            | Fuzzing & Testing        |
| **Echidna**    | Trail of Bits       | Fuzzer                   |
| **Optik**      | Trail of Bits       | Hybrid Fuzzing           |
| **Woke**       | Ackee Blockchain    | Cross-chain Testing      |
| **4naly3er**   | Picodes             | Scanner Code4rena        |
| **Manticore**  | Trail of Bits       | Symbolic Execution       |
| **Halmos**     | a16z                | Bounded Model Checker    |
| **SMTChecker** | Ethereum Foundation | Formal Verification      |
| **Mythril**    | Consensys           | Symbolic Execution       |
| **Pyrometer**  | Nascent             | (WIP) Symbolic Execution |

