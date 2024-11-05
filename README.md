
![KayeraOkey](https://i.pinimg.com/originals/31/24/73/312473c90b9906c7bcea7d820b9e5705.gif)

# Sokrates

https://kayera.uk/

https://kayera.uk/discord

https://kayera.uk/patreon

https://kayera.uk/linkedin

https://kayera.uk/github

### Nedir?

Sokrates, peşinizde dolaşacak küçük bir yapay zeka modelidir. OpenAI'ın API'ını kullanır. Ücretli OpenAI API'ı gerektirir.

## Özellikler

- Tek bir yapay zeka modeli kullanılabilir (GPT-3.5-turbo):
  - Açık kaynak kodlu olduğu için kod yapısı değiştirilerek model değiştirilebilir, koda etki etmeden ise tek model kullanılabilir.
- Açık Kaynak (Open Source)
- config.yml üzerinden API'ınızı kolaylıkla değiştirebilirsiniz.

## Nasıl kullanılır?

### Kendin buildle:

```bash
$ git clone https://github.com/kayeradev/Sokrates.git
$ dir Sokrates
$ ./gradlew build
```

Daha sonrasında .jar dosyası Sokrates/build/libs kısmına gelecektir.

### Plugin olarak indirip kullan:

https://github.com/kayeradev/Sokrates/releases sitesine gidin ve yüklenen son jar dosyasını indirin.

## OpenAI API'ını nasıl alacağım?

https://www.youtube.com/watch?v=OB99E7Y1cMA

## API'ı nasıl ayarlayacağım?

Plugini yükleyip sunucunuza restart attıktan sonra Sokrates klasöründeki config.yml dosyasına girin ve belirtilen yere API'ı yapıştırın.

## Nasıl kullanılır?

Sistem sadece **Kaayera** isimli oyuncularda çalışır. Bu nedenle açık kaynak kodunu düzenleyip Kaayera yazan yere kendi isimlerinizi yazmalısınız.

Sohbete "Sokrates" yazdıktan sonra yazdığınız metni input olarak alır. Örneğin:

"Sokrates bana hayvanat bahçesinde görebileceğin bir hayvan söyle."

## Bazı resimler:

![ornekresim](https://i.imgur.com/B3Gsgmj.png)
![ornekresim2](https://i.imgur.com/OCjMb4n.png)

## License

The MIT License (MIT)

Copyright (c) 2024-2025 Kayera

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies
of the Software, and to permit persons to whom the Software is furnished to do
so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
