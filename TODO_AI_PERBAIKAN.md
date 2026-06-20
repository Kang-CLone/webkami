# TODO - Perbaikan AI di wisudah.html

- [ ] Rapikan/mematikan script game (Flappy/Memory/Snake) dari `wisudah.html` agar tidak bikin error elemen tidak ada.
- [ ] Perbaiki AI chat agar:
  - hanya ada 1 implementasi fungsi `toggleChat`, `sendAIMsg`, `quickSend` (sekarang duplikat/bertabrakan).
  - tidak memanggil elemen game (`flappyCanvas`, `snakeCanvas`, `flappyBest`, dll) yang tidak ada di DOM.
  - kalau API anthropic gagal, tetap chat dengan local response (fallback) supaya AI tetap jalan.
- [ ] Rapikan event listener `window.load` / `checkBirthday` agar tidak dobel.
- [ ] Validasi fungsi input chat: Enter mengirim, tombol kirim kirim.
- [ ] Tes di browser: buka halaman, klik chat toggle, kirim pesan, dan pastikan tidak ada error console.

