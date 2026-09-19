# Yangi oʻzbek alifbosi uchun klaviatura terilmasi

![Klaviatura terlimasi rasmi](/assets/keyboard-layout.png)

## Klaviatura terilmasi xususiyatlari:

- **QWERTY** terilma asosida qurilgan va oʻrganish oson.
- Klaviaturada **Şş**, **Çç**, **Öö** va **Ğğ** belgilarini kiritish qulay va `AltGr` bosish talab etilmaydi.
- **Tutuq belgisi** uchun ishlatiladigan [U+02BC belgisini](<https://uz.wikipedia.org/wiki/%CA%BC_(belgi)>) kiritish uchun `\` tugmasini bosing.
- Eski alifbodagi Oʻ va Gʻ harflarida ishlatiladigan teskari vergulni ([ʻOkina belgisini](<https://uz.wikipedia.org/wiki/%CA%BB_(belgi)>)) kiritish uchun `Shift + \` kombinatsiyasini bosing.
- Ushbu klaviatura terilmasi koʻproq belgilarni kiritish uchun `AltGr` (odatda oʻng `Alt` tugmasi) tugmasidan foydalandi:
  - Nuqta vergulni kiritish uchun `AltGr + ş` kombinatsiyasini bosing.
  - Ikki nuqtani kiritish uchun `AltGr + Shift + ş` kombinatsiyasini bosing.
  - Apostrofni kiritish uchun `AltGr + ç` kombinatsiyasini bosing.
  - Qoʻshtirnoqni kiritish uchun `AltGr + Shift + ç` kombinatsiyasini bosing.
  - Chap kvadrat qavsni kiritish uchun `AltGr + ö` kombinatsiyasini bosing.
  - Chap figurali qavsni kiritish uchun `AltGr + Shift + ö` kombinatsiyasini bosing.
  - Oʻng kvadrat qavsni kiritish uchun `AltGr + ğ` kombinatsiyasini bosing.
  - Oʻng figurali qavsni kiritish uchun `AltGr + Shift + ğ` kombinatsiyasini bosing.
  - Teskari sleshni kiritish uchun `AltGr + ʼ (tutuq belgisi)` kombinatsiyasini bosing.
  - Tik chiziqni kiritish uchun `AltGr + Shift ʼ (tutuq belgisi)` kombinatsiyasini bosing.

## Windowsʼda oʻrnatish usuli:

1. [`setup.exe`](https://github.com/itsbilolbek/new-uzbek-keyboard/releases/download/v0.1/setup.exe) faylini yuklab oling.
2. `setup.exe` faylini ishga tushuring va klaviatura terilmasini oʻrnating
3. Til tanlash menyusida **Uzbek - new keyboard** variantini tanlang.

   ![Windows language select menu](/assets/windows-language-select.png)

## MacOSʼda oʻrnatish usuli:

1. [`ABC new Uzbek.bundle.zip`](https://github.com/itsbilolbek/new-uzbek-keyboard/releases/download/v0.1/ABC.new.Uzbek.bundle.zip) faylini yuklab oling va arxivdan chiqaring.

2. **Applications** ikonkasiga sudrab oʻrnating.

3. Sozlamalarda **Keyboard** boʻlimiga oʻting.

   ![Macos settings window](/assets/macos-settings-menu.png)

4. **Input sources** boʻlimidagi **Edit...** tugmasini bosing.

   ![Macos input sources menu](/assets/macos-input-sources-menu.png)
   ![Macos input sources menu](/assets/macos-input-sources-browse-menu.png)

5. Pastda chap tomondagi **+** belgisini bosib **ABC New Uzbek** klaviatura terilmasini qoʻshing.

## Linuxʼda oʻrnatish usuli:

1. [`uz`](/Linux/uz) faylini yuklab oling.
2. `/usr/share/X11/xkb/symbols/uz` faylini siz yuklab olgan fayl bilan almashtiring. Eski `uz` faylini zaxiralash maslahat etiladi.

   `sudo mv ~/Downloads/uz /usr/share/X11/xkb/symbols/uz`

3. Sozlamalarda klaviatura boʻlimiga oʻtib **Uzbek** variantini qoʻshing.
4. **Uzbek (Latin)** terilmasini tanlang.
