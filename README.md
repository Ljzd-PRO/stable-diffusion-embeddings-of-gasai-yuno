# Stable Diffusion embeddings of Gasai Yuno

## About
Stable Diffusion textual inversion embeddings, trained on NovelAI leak model "**animefull-latest**"[e6e8e1fc]

Trained on 49 pictures for 19600 steps, with 8 vectors per token setting.

## Usage

### The embedding files
**Path**: [`/gasai yuno/embeddings/`](https://github.com/Ljzd-PRO/stable-diffusion-embeddings-of-gasai-yuno/blob/main/gasai_yuno/embeddings/)

**The last embedding**(19600 steps): `gasai yuno-19600.pt`

### Preview images
[`/gasai yuno/image_embeddings/`](https://github.com/Ljzd-PRO/stable-diffusion-embeddings-of-gasai-yuno/blob/main/gasai_yuno/image_embeddings/) for preview for each embedding (mark with the number of step and the model hash).

[`/gasai yuno/image/`](https://github.com/Ljzd-PRO/stable-diffusion-embeddings-of-gasai-yuno/blob/main/gasai_yuno/image/) for preview for each embedding.

### The usage for [AUTOMATIC1111/stable-diffusion-webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui)
1. Place embedding file in `/embeddings` in the repository directory.
2. Use `[embedding_file_name]` in prompts.
> For example, if you use the embedding file `gasai yuno.pt`, then you should use `gasai yuno` in prompts  
> like `gasai yuno`, `a picture of gasai yuno`, `portrait of gasai yuno`
3. Generate image.

## Preview


## Dataset
Pictures from Pixiv and screenshot from Future Diary anime.

Artworks from Pixiv:
|   Title   |  Author  |   URL and artwork ID   |
| ---- | ---- | ---- |
| がさいさん | [山椒](https://www.pixiv.net/users/9226224) | [63487736](https://www.pixiv.net/artworks/63487736) |
| 大好きだよユッキー♥ | [Gadai](https://www.pixiv.net/users/1007481) | [23063160](https://www.pixiv.net/artworks/23063160) |
| 可愛い方の由乃ぴょん | [仙崎秋葉](https://www.pixiv.net/users/67968625) | [100940459](https://www.pixiv.net/artworks/100940459) |
| 我妻由乃 | [HaruON](https://www.pixiv.net/users/36637510) | [101514899](https://www.pixiv.net/artworks/101514899) |
| 我妻由乃 | [守屋光晴](https://www.pixiv.net/users/14706222) | [70103571](https://www.pixiv.net/artworks/70103571) |
| RED love | [shiyomi](https://www.pixiv.net/users/20334136) | [59145589](https://www.pixiv.net/artworks/59145589) |
| 我妻由乃 | [わんた](https://www.pixiv.net/users/80912901) | [97845620](https://www.pixiv.net/artworks/97845620) |
| ゆ の | [黒兎/Kurot](https://www.pixiv.net/users/42675) | [34668675](https://www.pixiv.net/artworks/34668675) |
| ゆの | [kana](https://www.pixiv.net/users/42986838) | [76219513](https://www.pixiv.net/artworks/76219513) |
| 我妻由乃（病み差分あり） | [池田](https://www.pixiv.net/users/49839934) | [85483740](https://www.pixiv.net/artworks/85483740) |
| 無題 | [らうと](https://www.pixiv.net/users/14438469) | [91165132](https://www.pixiv.net/artworks/91165132) |
| ね？ユッキー。 | [パトリシア@日曜 西R-23a](https://www.pixiv.net/users/2152) | [22784140](https://www.pixiv.net/artworks/22784140) |
| 何を犠牲にしてもも!!! | [衣のの](https://www.pixiv.net/users/1918464) | [22521906](https://www.pixiv.net/artworks/22521906) |
| 我妻由乃 | [snowprayer](https://www.pixiv.net/users/8284729) | [58407175](https://www.pixiv.net/artworks/58407175) |
| Untitled | [夜晴れ](https://www.pixiv.net/users/80331852) | [99177408](https://www.pixiv.net/artworks/99177408) |
| 我妻由乃 | [ハルマチ](https://www.pixiv.net/users/19770366) | [91344748](https://www.pixiv.net/artworks/91344748) |
| 恋 | [6sb](https://www.pixiv.net/users/15219049) | [82496336](https://www.pixiv.net/artworks/82496336) |
| 我妻由乃 | [orobou](https://www.pixiv.net/users/15353675) | [93475221](https://www.pixiv.net/artworks/93475221) |
| Yuno gasai | [IDHyury](https://www.pixiv.net/users/676725) | [61485116](https://www.pixiv.net/artworks/61485116) |
| 我妻由乃 | [絮果子](https://www.pixiv.net/users/16852016) | [61238906](https://www.pixiv.net/artworks/61238906) |
| 由乃っち | [フーポ▼C101申込済](https://www.pixiv.net/users/74538) | [75223350](https://www.pixiv.net/artworks/75223350) |
| 未来日記 | [Snozaki篠崎](https://www.pixiv.net/users/19476792) | [66798041](https://www.pixiv.net/artworks/66798041) |
| ！新しいメールが273件あります。 | [hatsuko](https://www.pixiv.net/users/237559) | [23817274](https://www.pixiv.net/artworks/23817274) |
| 由乃 | [庵壱波](https://www.pixiv.net/users/46935532) | [91291153](https://www.pixiv.net/artworks/91291153) |
| 我妻由乃 | [Rocks](https://www.pixiv.net/users/22741937) | [89901655](https://www.pixiv.net/artworks/89901655) |
| 我妻由乃 | [水表](https://www.pixiv.net/users/11319066) | [58224782](https://www.pixiv.net/artworks/58224782) |
| 由乃 | [仙崎秋葉](https://www.pixiv.net/users/67968625) | [100767496](https://www.pixiv.net/artworks/100767496) |
| 我妻由乃 | [tetto](https://www.pixiv.net/users/11837757) | [84061791](https://www.pixiv.net/artworks/84061791) |
| 我妻由乃 | [ナツメグ](https://www.pixiv.net/users/177117) | [100480864](https://www.pixiv.net/artworks/100480864) |
| 我妻由乃/Gasai Yuno | [Leemun](https://www.pixiv.net/users/45090103) | [82414019](https://www.pixiv.net/artworks/82414019) |
| 我妻由乃 | [Mikako](https://www.pixiv.net/users/35193903) | [71460217](https://www.pixiv.net/artworks/71460217) |
| 20220429 | [Kevn](https://www.pixiv.net/users/2836899) | [97976315](https://www.pixiv.net/artworks/97976315) |
| 我妻由乃 | [たけもうち（旧 竹内元紀）](https://www.pixiv.net/users/1470854) | [61773015](https://www.pixiv.net/artworks/61773015) |
| 2022/7/7 由乃 | [Iddoraemon](https://www.pixiv.net/users/12365802) | [99570019](https://www.pixiv.net/artworks/99570019) |
| 我妻由乃 | [草莓蘇(雁羽)](https://www.pixiv.net/users/72625752) | [94889756](https://www.pixiv.net/artworks/94889756) |
| 由乃 | [Shotz](https://www.pixiv.net/users/8321385) | [91247145](https://www.pixiv.net/artworks/91247145) |
| 我妻由乃 | [こうこ](https://www.pixiv.net/users/1490115) | [23290423](https://www.pixiv.net/artworks/23290423) |
| yuno | [のまる](https://www.pixiv.net/users/7842054) | [62962913](https://www.pixiv.net/artworks/62962913) |
| 我妻由乃 | [RelaxJon](https://www.pixiv.net/users/3548205) | [76075748](https://www.pixiv.net/artworks/76075748) |
| ❤️ | [49m](https://www.pixiv.net/users/27105744) | [80398336](https://www.pixiv.net/artworks/80398336) |
| 我妻由乃 | [神崎涼子](https://www.pixiv.net/users/14344686) | [78256946](https://www.pixiv.net/artworks/78256946) |
| ユッキー……♡ | [tetto](https://www.pixiv.net/users/11837757) | [89767327](https://www.pixiv.net/artworks/89767327) |
| 我妻由乃 | [viscum](https://www.pixiv.net/users/20951095) | [82577229](https://www.pixiv.net/artworks/82577229) |
