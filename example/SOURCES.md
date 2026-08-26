# Example artwork sources

These files are source-artwork examples for testing `dounai-art-convertor`. They are not generated outputs.

| Local file | Category | Work | Artist / attribution | Source | Rights status |
| --- | --- | --- | --- | --- | --- |
| `assets/oil-liberty-leading-the-people.jpg` | Oil painting | *Liberty Leading the People* (1830) | Eugène Delacroix (1798–1863) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Eug%C3%A8ne_Delacroix_-_La_libert%C3%A9_guidant_le_peuple.jpg) | Public domain; faithful reproduction of a public-domain two-dimensional artwork |
| `assets/abstract-the-city-rises.jpg` | Abstract / Futurist painting | *The City Rises* (1910) | Umberto Boccioni (1882–1916) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:The_City_Rises_by_Umberto_Boccioni_1910.jpg) | Public domain; faithful reproduction of a public-domain two-dimensional artwork |
| `assets/chinese-night-revels-of-han-xizai.jpg` | Chinese painting | *The Night Revels of Han Xizai* | Traditionally attributed to Gu Hongzhong (937–975) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Gu_Hongzhong_13.jpg) | Public domain; faithful reproduction of a public-domain two-dimensional artwork |
| `assets/impressionism-woman-with-a-parasol.jpg` | Impressionism | *Woman with a Parasol – Madame Monet and Her Son* (1875) | Claude Monet (1840–1926) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Claude_Monet_-_Woman_with_a_Parasol_-_Madame_Monet_and_Her_Son_-_Google_Art_Project.jpg) | Public domain; faithful reproduction of a public-domain two-dimensional artwork |
| `assets/cubism-portrait-of-pablo-picasso.jpg` | Cubism | *Portrait of Pablo Picasso* (1912) | Juan Gris (1887–1927) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Juan_Gris_-_Portrait_of_Pablo_Picasso_-_Google_Art_Project.jpg) | Public domain; faithful reproduction of a public-domain two-dimensional artwork |
| `assets/expressionism-the-scream.jpg` | Expressionism | *The Scream* (1893) | Edvard Munch (1863–1944) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Edvard_Munch_-_The_Scream.jpg) | Public domain; faithful reproduction of a public-domain two-dimensional artwork |
| `assets/art-nouveau-the-kiss.jpg` | Vienna Secession / Art Nouveau | *The Kiss* (1907–1908) | Gustav Klimt (1862–1918) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Klimt_-_The_Kiss.jpg) | Public domain; faithful reproduction of a public-domain two-dimensional artwork |
| `assets/ukiyo-e-sudden-shower-over-shin-ohashi.jpg` | Ukiyo-e woodblock print | *Sudden Shower over Shin-Ōhashi Bridge and Atake* (1857) | Utagawa Hiroshige (1797–1858) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Hiroshige%2C_Sudden_shower_over_Shin-%C5%8Chashi_bridge_and_Atake%2C_1857.jpg) | Public domain; faithful reproduction of a public-domain two-dimensional artwork |

The repository copies are resized Wikimedia Commons derivatives chosen to keep the GitHub download size practical. Check each linked Commons file page for its full provenance and jurisdiction-specific reuse notes.

## Converted example outputs

The following AI-edited examples were produced from the source artworks above using the full-figure mode of `dounai-art-convertor`:

| Source artwork | Converted output | Demonstrated behavior |
| --- | --- | --- |
| `assets/oil-liberty-leading-the-people.jpg` | `assets/oil-liberty-leading-the-people-converted.png` | Clearly female central figure becomes Doubao; other living figures become Nailongs while Romantic oil-painting composition is preserved |
| `assets/abstract-the-city-rises.jpg` | `assets/abstract-the-city-rises-converted.png` | Gender-uncertain human figures become Nailongs while horses and Futurist brushwork are preserved |
| `assets/chinese-night-revels-of-han-xizai.jpg` | `assets/chinese-night-revels-of-han-xizai-converted.png` | Court women become Doubao and male or uncertain figures become Nailongs in an aged Chinese handscroll style |
| `assets/impressionism-woman-with-a-parasol.jpg` | `assets/impressionism-woman-with-a-parasol-converted.png` | Camille Monet becomes Doubao and her son becomes Nailong while windblown Impressionist light and brushwork are preserved |
| `assets/cubism-portrait-of-pablo-picasso.jpg` | `assets/cubism-portrait-of-pablo-picasso-converted.png` | The male portrait becomes a Nailong reconstructed through analytic Cubist planes while hairstyle, suit and paper remain recognizable |
| `assets/expressionism-the-scream.jpg` | `assets/expressionism-the-scream-converted.png` | The central uncertain figure and distant figures become Nailongs while the original Expressionist gesture and anxious surface are preserved |
| `assets/art-nouveau-the-kiss.jpg` | `assets/art-nouveau-the-kiss-converted.png` | The woman becomes Doubao and the man becomes Nailong while the embrace, floral head ornaments and gold decorative field are preserved |
| `assets/ukiyo-e-sudden-shower-over-shin-ohashi.jpg` | `assets/ukiyo-e-sudden-shower-over-shin-ohashi-converted.png` | Gender-uncertain pedestrians and boatman become Nailongs while hats, rain gear, bridge geometry, cartouches and ukiyo-e print language are preserved |

