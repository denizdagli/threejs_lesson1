# Ders 1: Ilk 3D Kupum

1. Bu klasordeki `index.html` dosyasina cift tikla, tarayicida donen kupu goreceksin.
2. `index.html` dosyasini VS Code ile ac ve kodu degistir.
3. Degisiklikten sonra: Ctrl+S (kaydet), tarayicida F5 (yenile).

Onemli: `three.min.js` ve `index.html` AYNI klasorde kalmali.

## Bozma Oyunu
Her seferinde sadece TEK sayiyi degistir, ne oldugunu not et:

- `BoxGeometry(2, 2, 2)` -> `BoxGeometry(4, 1, 1)`
- `kup.rotation.y += 0.02` -> `+= 0.2`
- `kamera.position.z = 5` -> `= 2` ve sonra `= 20`
- `0x0b1d3a` -> `0xff3366`
- `new THREE.MeshNormalMaterial()` -> `new THREE.MeshNormalMaterial({ wireframe: true })`
- `BoxGeometry` -> `SphereGeometry(1.5, 32, 32)`

## Sayfa bos kalirsa
F12'ye bas, Console sekmesine bak, kirmizi yaziyi oku.

## Gorev
Kupu kendi hayal ettigin bir nesneye donustur: renk, sekil, boyut ve hizi sec.
