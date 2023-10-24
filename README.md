// Input pendapatan salesman pada hari itu
let pendapatan = 600000;

// Inisialisasi variabel uangJasa dan komisi
let uangJasa = 0;
let komisi = 0;

// Hitung uang jasa dan komisi berdasarkan pendapatan
if (pendapatan <= 200000) {
  uangJasa = 10000;
  komisi = pendapatan * 0.1;
} else if (pendapatan <= 500000) {
  uangJasa = 20000;
  komisi = pendapatan * 0.15;
} else {
  uangJasa = 30000;
  komisi = pendapatan * 0.2;
}

// Hitung total bayaran
let totalBayaran = uangJasa + komisi;

// Tampilkan hasil
console.log(`Pendapatan: Rp. ${pendapatan}`);
console.log(`Uang jasa: Rp. ${uangJasa}`);
console.log(`Komisi: Rp. ${komisi}`);
console.log(`Total bayaran: Rp. ${totalBayaran}`);
