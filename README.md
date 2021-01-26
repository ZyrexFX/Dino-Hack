## Dino Google Game Hack

Simpel code buat dino game. Silahkan show off score nya ke temen...
![Dino Game](https://cdn.discordapp.com/attachments/638665637111267332/803569019554365440/unknown.png)

### How to haxx

- Buka gamenya dulu, bisa offline atau biar ga ribet langsung ke [sini](https://camo.githubusercontent.com/d2c710d52f983f44473352d76d2669cba180f13fa4ed445582d774a51c383b8c/68747470733a2f2f63646e2e646973636f72646170702e636f6d2f6174746163686d656e74732f3633383636353633373131313236373333322f3830333536393031393535343336353434302f756e6b6e6f776e2e706e67)
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
