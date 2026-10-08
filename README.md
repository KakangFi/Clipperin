# ClipForge Lite
Versi ringan untuk HP/RAM terbatas.

Berbeda dari versi FFmpeg, versi ini memakai `HTMLVideoElement.captureStream()` + `MediaRecorder`. Video tidak dimasukkan ke memory WebAssembly dan tidak perlu mengunduh FFmpeg.

Kelebihan:
- jauh lebih ringan di RAM
- upload lokal
- 1–10 clip
- 15/30/45/60 detik
- preview & download
- GitHub Pages gratis

Catatan:
- output WebM, bukan MP4
- proses berlangsung hampir realtime (clip 30 detik membutuhkan sekitar 30 detik untuk direkam)
- dukungan captureStream/MediaRecorder bergantung browser; Chrome Android terbaru paling disarankan
- versi ini belum AI highlight detection
