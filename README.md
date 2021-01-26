## Dino Google Game Hack

Simpel code buat dino game. Silahkan show off score nya ke temen...
![Dino Game](https://cdn.discordapp.com/attachments/638665637111267332/803569019554365440/unknown.png)

### How to haxx

- Buka gamenya dulu, bisa offline atau biar ga ribet langsung ke [sini](chrome://dino)
- Tekan ``F12`` di keyboard, kalo gada keyboard bisa klik kanan mouse lalu ``inspect``
- Klik tab ``console``.

### No_clip.exe

Ketik command di bawah dalam tab console untuk membuat dino tembus terhadap obstacle.

```js
Runner.prototype.gameOver = function(){}
```

#### Cheat speed

Atur kecepatan lari dino.

```js
Runner.instance_.setSpeed(300) //tinggal ubah angka buat atur speed.
```

### Jump Code

Atur tinggi rendah lompatan dino.

```js
Runner.instance_.tRex.setJumpVelocity(10) //ubah angka
```

### Snippet

To infinity and beyond

```js
var original = Runner.prototype.gameOver

Runner.prototype.gameOver = function(){}

Runner.instance_.tRex.setJumpVelocity(30)
Runner.instance_.setSpeed(300)
```

Kalo uda bosen...

```js
Runner.prototype.gameOver = original
```
