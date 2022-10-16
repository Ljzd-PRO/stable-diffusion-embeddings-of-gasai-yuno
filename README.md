# Stable Diffusion embeddings of Gasai Yuno

## ❓ About
Stable Diffusion textual inversion embeddings, trained on NovelAI leak model **`"animefull-latest"[e6e8e1fc]`**

Trained on 49 pictures for 19600 steps, with 8 vectors per token setting.

## 📖 Usage

### 📁 The embedding files
**Path**: [`/gasai yuno/embeddings/`](https://github.com/Ljzd-PRO/stable-diffusion-embeddings-of-gasai-yuno/tree/main/gasai%20yuno/embeddings)

**The last embedding**(19600 steps): `gasai yuno-19600.pt` [**🔗Download**](https://github.com/Ljzd-PRO/stable-diffusion-embeddings-of-gasai-yuno/raw/main/gasai%20yuno/embeddings/gasai%20yuno-9800.pt)

### 📷 Preview images
| [`/gasai yuno/image_embeddings/`](https://github.com/Ljzd-PRO/stable-diffusion-embeddings-of-gasai-yuno/tree/main/gasai%20yuno/image_embeddings/)<br/>Preview for each embedding (mark with the number of step and the model hash). | [`/gasai yuno/image/`](https://github.com/Ljzd-PRO/stable-diffusion-embeddings-of-gasai-yuno/tree/main/gasai%20yuno/images/)<br/>Preview for each embedding. |
| ---- | ---- |
| ![image_embeddings](https://user-images.githubusercontent.com/63289359/195997003-e3da93f6-bba5-4bce-961a-0981b280c620.png) | ![image](https://user-images.githubusercontent.com/63289359/195997017-b32c1808-d6b8-44df-8600-0360c652c039.png) |

### 📖 The usage for [AUTOMATIC1111/stable-diffusion-webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui)
1. Place embedding file in `/embeddings` in the repository directory.
2. Use `[embedding_file_name]` in prompts.
> For example, if you use the embedding file `gasai yuno.pt`, then you should use `gasai yuno` in prompts  
> like `gasai yuno`, `a picture of gasai yuno`, `portrait of gasai yuno`
3. Generate image.

## 📷 Preview
```
a nice picture of gasai yuno,masterpiece,best quality,official art,extremely detailed CG unity 8k wallpaper,arm up,hands up,smile,under sakura tree
Negative prompt: lowres, bad anatomy, bad hands, text, error, missing fingers, extra digit, fewer digits, cropped, worst quality, low quality, normal quality, jpeg artifacts, signature, watermark, username, blurry, bad feet,no person in the picture
Steps: 40, Sampler: Euler a, CFG scale: 7, Seed: 3537605807, Size: 512x512, Model hash: e6e8e1fc

Used embeddings: gasai yuno [5d63]
```
![IMG_2987](https://user-images.githubusercontent.com/63289359/196021552-ab79e7dc-3275-4c78-8a79-51a18cc95516.png)

---

```
a nice picture of gasai yuno,masterpiece,best quality,official art,extremely detailed CG unity 8k wallpaper,arm up,hands up,smile,in a park
Negative prompt: lowres, bad anatomy, bad hands, text, error, missing fingers, extra digit, fewer digits, cropped, worst quality, low quality, normal quality, jpeg artifacts, signature, watermark, username, blurry, bad feet,no person in the picture
Steps: 60, Sampler: Euler a, CFG scale: 7, Seed: 1935268946, Size: 512x512, Model hash: e6e8e1fc

Used embeddings: gasai yuno [5d63]
```
![IMG_2988](https://user-images.githubusercontent.com/63289359/196025865-9e125898-c41b-4429-9ad0-768f73f86a64.png)

---

```
a nice picture of gasai yuno,masterpiece,best quality,official art,extremely detailed CG unity 8k wallpaper,arm up,hands up,holding one knife,smile,in classroom
Negative prompt: lowres, bad anatomy, bad hands, text, error, missing fingers, extra digit, fewer digits, cropped, worst quality, low quality, normal quality, jpeg artifacts, signature, watermark, username, blurry, bad feet,no person in the picture
Steps: 40, Sampler: Euler a, CFG scale: 7, Seed: 2038539810, Size: 512x512, Model hash: e6e8e1fc

Used embeddings: gasai yuno [5d63]
```
![IMG_2989](https://user-images.githubusercontent.com/63289359/196025983-ecabd087-461c-4d19-92f5-4723e2344ea7.png)

---

```
a nice picture of gasai yuno,masterpiece,best quality,official art,extremely detailed CG unity 8k wallpaper,cool,clear face,in classroom
Negative prompt: lowres, bad anatomy, bad hands, text, error, missing fingers, extra digit, fewer digits, cropped, worst quality, low quality, normal quality, jpeg artifacts, signature, watermark, username, blurry, bad feet,no person in the picture,knife in hand
Steps: 40, Sampler: Euler a, CFG scale: 7, Seed: 1489230976, Size: 512x512, Model hash: e6e8e1fc

Used embeddings: gasai yuno [5d63]
```
![IMG_2991](https://user-images.githubusercontent.com/63289359/196026080-d06e44cd-55d3-4d89-b4f4-ba3d54a4ea48.png)

---

```
a nice picture of gasai yuno,masterpiece,best quality,official art,extremely detailed CG unity 8k wallpaper,cool,clear face,in classroom
Negative prompt: lowres, bad anatomy, bad hands, text, error, missing fingers, extra digit, fewer digits, cropped, worst quality, low quality, normal quality, jpeg artifacts, signature, watermark, username, blurry, bad feet,no person in the picture,knife in hand
Steps: 40, Sampler: Euler a, CFG scale: 7, Seed: 1489230973, Size: 512x512, Model hash: e6e8e1fc

Used embeddings: gasai yuno [5d63]
```
![IMG_2993](https://user-images.githubusercontent.com/63289359/196026453-9b3f9505-bf52-497b-931c-bb4a31a4c7dc.png)

---

```
a nice picture of gasai yuno,masterpiece,best quality,official art,extremely detailed CG unity 8k wallpaper,cool,clear face,in classroom,sitting
Negative prompt: lowres, bad anatomy, bad hands, text, error, missing fingers, extra digit, fewer digits, cropped, worst quality, low quality, normal quality, jpeg artifacts, signature, watermark, username, blurry, bad feet,no person in the picture,knife in hand
Steps: 40, Sampler: Euler a, CFG scale: 7, Seed: 3022414708, Size: 512x512, Model hash: e6e8e1fc

Used embeddings: gasai yuno [5d63]
```
![IMG_2995](https://user-images.githubusercontent.com/63289359/196026481-57db3847-ca53-4952-af8a-78bc22309cd8.png)

---

```
a nice picture of gasai yuno,masterpiece,best quality,official art,extremely detailed CG unity 8k wallpaper,cool,clear face,in classroom,sitting,soft
Negative prompt: lowres, bad anatomy, bad hands, text, error, missing fingers, extra digit, fewer digits, cropped, worst quality, low quality, normal quality, jpeg artifacts, signature, watermark, username, blurry, bad feet,no person in the picture,knife in hand
Steps: 40, Sampler: Euler a, CFG scale: 7, Seed: 1779686079, Size: 512x512, Model hash: e6e8e1fc

Used embeddings: gasai yuno [5d63]
```
![IMG_2996](https://user-images.githubusercontent.com/63289359/196026546-eadd0cd6-32d6-4da7-9cc5-3b8dc48da422.png)

---

```
a nice picture of gasai yuno,masterpiece,best quality,official art,extremely detailed CG unity 8k wallpaper,cool,clear face,in classroom,sitting,soft
Negative prompt: lowres, bad anatomy, bad hands, text, error, missing fingers, extra digit, fewer digits, cropped, worst quality, low quality, normal quality, jpeg artifacts, signature, watermark, username, blurry, bad feet,no person in the picture,knife in hand
Steps: 40, Sampler: Euler a, CFG scale: 7, Seed: 1779686078, Size: 512x512, Model hash: e6e8e1fc

Used embeddings: gasai yuno [5d63]
```
![IMG_2997](https://user-images.githubusercontent.com/63289359/196026592-9361d58f-99b5-4eb8-bd42-88b6a768d210.png)

---

```
a nice picture of gasai yuno,masterpiece,best quality,official art,extremely detailed CG unity 8k wallpaper,cool,clear face,in classroom,sitting,soft
Negative prompt: lowres, bad anatomy, bad hands, text, error, missing fingers, extra digit, fewer digits, cropped, worst quality, low quality, normal quality, jpeg artifacts, signature, watermark, username, blurry, bad feet,no person in the picture,knife in hand
Steps: 40, Sampler: Euler a, CFG scale: 7, Seed: 2750656602, Size: 1024x1024, Model hash: e6e8e1fc

Used embeddings: gasai yuno [5d63]
```
![IMG_2998](https://user-images.githubusercontent.com/63289359/196026609-2b1f159e-64a9-4fd4-9cab-c1df20583c23.png)

---

```
a nice picture of gasai yuno,masterpiece,best quality,official art,extremely detailed CG unity 8k wallpaper,cool,clear face,in classroom,sitting,soft
Negative prompt: lowres, bad anatomy, bad hands, text, error, missing fingers, extra digit, fewer digits, cropped, worst quality, low quality, normal quality, jpeg artifacts, signature, watermark, username, blurry, bad feet,no person in the picture,knife in hand
Steps: 40, Sampler: Euler a, CFG scale: 7, Seed: 2750656603, Size: 1024x1024, Model hash: e6e8e1fc

Used embeddings: gasai yuno [5d63]
```
![IMG_2999](https://user-images.githubusercontent.com/63289359/196026720-e96d2be4-fd59-47bd-86ba-8d44c466380a.png)

---

```
a nice picture of gasai yuno,masterpiece,best quality,official art,extremely detailed CG unity 8k wallpaper,cool,clear face,in park,sitting,soft
Negative prompt: lowres, bad anatomy, bad hands, text, error, missing fingers, extra digit, fewer digits, cropped, worst quality, low quality, normal quality, jpeg artifacts, signature, watermark, username, blurry, bad feet,no person in the picture,knife in hand,multiple person
Steps: 40, Sampler: Euler a, CFG scale: 7, Seed: 2689790077, Size: 1024x1024, Model hash: e6e8e1fc

Used embeddings: gasai yuno [5d63]
```
![IMG_3001](https://user-images.githubusercontent.com/63289359/196026746-36b69f54-8b37-4739-9505-0f695a41870b.png)

---

```
a nice picture of gasai yuno,masterpiece,best quality,official art,extremely detailed CG unity 8k wallpaper,cool,clear face,in park,soft,sitting
Negative prompt: lowres, bad anatomy, bad hands, text, error, missing fingers, extra digit, fewer digits, cropped, worst quality, low quality, normal quality, jpeg artifacts, signature, watermark, username, blurry, bad feet,no person in the picture,multiple person
Steps: 40, Sampler: Euler a, CFG scale: 7, Seed: 1214961476, Size: 1024x1024, Model hash: e6e8e1fc

Used embeddings: gasai yuno [5d63]
```
![IMG_2391](https://user-images.githubusercontent.com/63289359/196026806-71834ae8-f93f-4570-84c3-8f23536e6de2.png)

## 🗃️ Dataset
Pictures from Pixiv and screenshot from Future Diary anime.

**🙏 Artworks from Pixiv:**
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
