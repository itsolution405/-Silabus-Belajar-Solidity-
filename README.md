# Silabus-Belajar-Solidity

Berikut **silabus pembelajaran pemrograman Solidity** yang bisa kamu ikuti secara bertahap, dari dasar hingga menengah/lanjutan. Cocok untuk pemula yang ingin mengembangkan smart contract di Ethereum.

---

## 🧠 **Silabus Belajar Solidity (Level Pemula – Menengah)**

### 🟢 **Level 1: Pengenalan Blockchain & Ethereum**

1. Apa itu Blockchain
2. Apa itu Ethereum dan Smart Contract
3. Perbedaan antara Ethereum, Bitcoin, dan jaringan lainnya
4. Apa itu EVM (Ethereum Virtual Machine)
5. Tools penting:

   * MetaMask
   * Remix IDE
   * Ganache (local blockchain)
   * Hardhat / Truffle (opsional, nanti)

---

### 🟢 **Level 2: Dasar-Dasar Solidity**

1. Struktur file `.sol` (pragma, kontrak, dll)
2. Tipe data dasar:

   * `uint`, `int`, `bool`, `address`, `string`, `bytes`
3. Variabel dan fungsi
4. Visibility: `public`, `private`, `internal`, `external`
5. Fungsi pembanding dan logika (`if`, `require`, dll)
6. Event & Emit

---

### 🟡 **Level 3: Struktur Data Solidity**

1. **Array** (static & dynamic)
2. **Struct**
3. **Mapping**
4. Penggunaan kombinasi mapping + struct
5. `enum` dan penggunaannya

---

### 🟡 **Level 4: Function Lanjutan**

1. **Constructor**
2. **Modifier** (contoh: akses admin)
3. Fungsi `view`, `pure`, dan `payable`
4. Error handling (`require`, `assert`, `revert`)
5. Fungsi fallback dan receive

---

### 🟡 **Level 5: Manajemen Aset dan Transaksi**

1. Mengelola ETH: kirim dan terima Ether
2. Fungsi `payable` dan `msg.value`
3. `msg.sender`, `msg.data`, `tx.origin`
4. Menarik dana (withdraw pattern)
5. Gas dan optimasi kode

---

### 🟠 **Level 6: Interaksi Kontrak & Keamanan**

1. Memanggil kontrak lain (interface)
2. DelegateCall dan Call
3. Keamanan:

   * Reentrancy
   * Integer overflow (sebelum Solidity 0.8)
   * Access control
   * Front-running

---

### 🔵 **Level 7: Project Mini – DApps**

1. **Membuat Smart Contract:**

   * Voting
   * Crowdfunding
   * Token ERC-20
2. Deploy ke Remix & test di Rinkeby atau Sepolia
3. Connect dengan frontend (HTML/React + Web3.js atau Ethers.js)

---

### 🔴 **Level 8: Tools dan Testing**

1. Hardhat atau Truffle untuk testing & deploy
2. Menulis unit test dengan JavaScript atau TypeScript
3. Coverage & debugging
4. Simulasi transaksi & gas estimation

---

## 📦 **Bonus: Smart Contract Standar**

* ERC-20: Token standar
* ERC-721: NFT
* ERC-1155: Multi-token
* OpenZeppelin Library
