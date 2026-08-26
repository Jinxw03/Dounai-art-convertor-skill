# 🎨 Doubao & Nailong Artwork Converter

Transform figures in existing artworks into recognizable **Doubao** or **Nailong** characters while preserving the source composition, pose, clothing, medium, lighting, and historical atmosphere.

> [!IMPORTANT]
> This is an unofficial, non-commercial creative and research project. Commercial use is prohibited under the custom [LICENSE](./LICENSE.md). Character names, designs, and related rights remain with their respective owners.

---

## 📖 About

This Codex skill makes character replacement feel native to the original artwork:

- 👩 Clearly female figures become **Doubao**.
- 🐉 Male or gender-uncertain figures become **Nailong**.
- 🎭 Hair, headwear, clothing, gesture, and identity cues are preserved when they help the source character remain recognizable.
- 🖌️ Brushwork, texture, palette, lighting, perspective, and period atmosphere stay faithful to the original.
- ✨ The result should read instantly as Doubao or Nailong without looking pasted in.

---

## 🖼️ Before & After Gallery

<table>
  <tr>
    <th>Style</th>
    <th>Before</th>
    <th>After</th>
  </tr>
  <tr>
    <td><b>Romanticism / Oil Painting</b><br><i>Liberty Leading the People</i></td>
    <td><img src="./example/assets/oil-liberty-leading-the-people.jpg" alt="Original Romantic oil painting" width="320"></td>
    <td><img src="./example/assets/oil-liberty-leading-the-people-converted.png" alt="Romantic oil painting converted to Doubao and Nailong" width="320"></td>
  </tr>
  <tr>
    <td><b>Futurism / Abstract</b><br><i>The City Rises</i></td>
    <td><img src="./example/assets/abstract-the-city-rises.jpg" alt="Original Futurist painting" width="320"></td>
    <td><img src="./example/assets/abstract-the-city-rises-converted.png" alt="Futurist painting converted to Doubao and Nailong" width="320"></td>
  </tr>
  <tr>
    <td><b>Chinese Handscroll</b><br><i>The Night Revels of Han Xizai</i></td>
    <td><img src="./example/assets/chinese-night-revels-of-han-xizai.jpg" alt="Original Chinese handscroll" width="320"></td>
    <td><img src="./example/assets/chinese-night-revels-of-han-xizai-converted.png" alt="Chinese handscroll converted to Doubao and Nailong" width="320"></td>
  </tr>
  <tr>
    <td><b>Impressionism</b><br><i>Woman with a Parasol</i></td>
    <td><img src="./example/assets/impressionism-woman-with-a-parasol.jpg" alt="Original Impressionist painting" width="320"></td>
    <td><img src="./example/assets/impressionism-woman-with-a-parasol-converted.png" alt="Impressionist painting converted to Doubao" width="320"></td>
  </tr>
  <tr>
    <td><b>Cubism</b><br><i>Portrait of Pablo Picasso</i></td>
    <td><img src="./example/assets/cubism-portrait-of-pablo-picasso.jpg" alt="Original Cubist portrait" width="320"></td>
    <td><img src="./example/assets/cubism-portrait-of-pablo-picasso-converted.png" alt="Cubist portrait converted to Nailong" width="320"></td>
  </tr>
  <tr>
    <td><b>Expressionism</b><br><i>The Scream</i></td>
    <td><img src="./example/assets/expressionism-the-scream.jpg" alt="Original Expressionist painting" width="320"></td>
    <td><img src="./example/assets/expressionism-the-scream-converted.png" alt="Expressionist painting converted to Nailong" width="320"></td>
  </tr>
  <tr>
    <td><b>Vienna Secession</b><br><i>The Kiss</i></td>
    <td><img src="./example/assets/art-nouveau-the-kiss.jpg" alt="Original Vienna Secession painting" width="320"></td>
    <td><img src="./example/assets/art-nouveau-the-kiss-converted.png" alt="Vienna Secession painting converted to Doubao and Nailong" width="320"></td>
  </tr>
  <tr>
    <td><b>Ukiyo-e</b><br><i>Sudden Shower over Shin-Ohashi Bridge</i></td>
    <td><img src="./example/assets/ukiyo-e-sudden-shower-over-shin-ohashi.jpg" alt="Original ukiyo-e print" width="320"></td>
    <td><img src="./example/assets/ukiyo-e-sudden-shower-over-shin-ohashi-converted.png" alt="Ukiyo-e print converted to Nailong" width="320"></td>
  </tr>
</table>

Source and provenance notes are listed in [example/SOURCES.md](./example/SOURCES.md).

---

## 📋 Contents

- [Installation](#-installation)
- [Usage](#-usage)
- [Core Principles](#-core-principles)
- [Repository Structure](#-repository-structure)
- [Support the Project](#-support-the-project)
- [License](#-license)

---

## 🚀 Installation

Copy this repository into your Codex skills directory:

```text
~/.codex/skills/dounai-art-convertor/
```

Restart Codex or reload skills after copying the folder.

## 🪄 Usage

Attach an existing artwork and ask Codex to use the **dounai-art-convertor** skill.

Example:

```text
Use dounai-art-convertor to transform the figures in this artwork.
Preserve the original composition, clothing, lighting, and painting style.
```

This skill is intended for existing artworks with identifiable figures. It is not intended for unrelated text-to-image scenes, generic dragons, or single-character transformations outside the Doubao/Nailong mapping.

---

## 💡 Core Principles

- ✅ Recognizable at first glance as **Doubao** or **Nailong**.
- ✅ Faithful to the source pose, composition, costume, and medium.
- ✅ Natural integration with no pasted-on or costume-mask appearance.
- ✅ Original hair and headwear retained when they support identity.
- ✅ Nailong anatomy follows the recognizable rounded torso, short limbs, small green eyes, and cream belly.
- ❌ No generic anime substitute for Doubao.
- ❌ No generic yellow dragon substitute for Nailong.
- ❌ No unnecessary background redesign.

Detailed direction:

- [Doubao Art Direction](./references/doubao-art-direction.md)
- [Nailong Art Direction](./references/nailong-art-direction.md)

---

## 📁 Repository Structure

```text
dounai-art-convertor/
├── SKILL.md
├── README.md
├── LICENSE.md
├── agents/
│   └── openai.yaml
├── references/
│   ├── doubao-art-direction.md
│   └── nailong-art-direction.md
├── example/
│   ├── SOURCES.md
│   └── assets/
└── pay/
    ├── alipay.jpg
    └── wechat-pay.jpg
```

---

## ☕ Support the Project

If this project is useful to you, a **Star ⭐** is greatly appreciated. You can also support continued improvements with Alipay or WeChat Pay.

<table>
  <tr>
    <th>Alipay</th>
    <th>WeChat Pay</th>
  </tr>
  <tr>
    <td><img src="./pay/alipay.jpg" alt="Alipay donation QR code" width="320"></td>
    <td><img src="./pay/wechat-pay.jpg" alt="WeChat Pay donation QR code" width="320"></td>
  </tr>
</table>

Thank you for supporting the project! 💙💚

---

## 📄 License

This project uses a custom [Non-Commercial License](./LICENSE.md).

- Personal, educational, academic, research, and other strictly non-commercial uses are permitted under its terms.
- Commercial use, paid services, advertising, merchandise, client work, and monetized content are prohibited without prior written permission from every applicable rights holder.
- Third-party artwork and character rights are not relicensed by this repository.

Please read the full license before using or redistributing project materials.
