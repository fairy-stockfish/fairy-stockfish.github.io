---
layout: page
title: Download NNUE
permalink: /nnue/
---

By default Fairy-Stockfish uses a handcrafted evaluation function in order to evaluate chess variant positions. Variant-specific NNUE (efficiently updatable neural network) evaluation files can be used to improve playing strength compared to the handcrafted evaluation. If you want to learn more about NNUE, see the [NNUE introduction](/about-nnue/), otherwise see the downloads below.

### Current best NNUE networks

This is an alphabetical list of current best variant NNUE networks available at [this google drive folder](https://drive.google.com/drive/folders/1m5PpiI3Kjzk_ow7F5RkwKnbO0Td-qb9J?usp=sharing) that are compatible with the latest Fairy-Stockfish release and development version. The listed Elo difference is the improvement of the respective NNUE network over the built-in handcrafted/classical evaluation function, i.e., the one that is used when not loading an NNUE file.

|  variant | network | Elo vs. classical | date | author | comment |
|---|---|---|---|---|---|
| 3check  | [3check-cb5f517c228b.nnue](https://drive.google.com/u/0/uc?id=1z5oUQbqiE0ZIoQ8Z64y2lF91Rz1rUoWP&export=download) | +200 | | nishibuya in discord |
| 5check  |  |  | | | Compatible to 3check networks
| active | [active-41937adf950a.nnue](https://drive.google.com/u/0/uc?id=10hbC8MNAvWWX8GJOhXiOkmqVX5XM-hSa&export=download) | +273 | 2025/07/31 | belzedar_ in discord |
| ai-wok | [ai-wok-530fdd028e59.nnue](https://drive.google.com/u/0/uc?id=1x0Yk__LJEU91D0kjyCmdJc0qcf_nYDYU&export=download) | +352 | 2022/04/15 | belzedar_ in discord |
| ajax-orthodox | [ajax-orthodox-8755d3f59603.nnue](https://drive.google.com/u/0/uc?id=1ESSYMP5IjBV980_KLSK3rR4tUsOt_NBs&export=download) | +113 | 2025/07/31 | belzedar_ in discord |
| alapo | [alapo-d77bda8b533d.nnue](https://drive.google.com/u/0/uc?id=1Ggp5wAfRpoGLSac__snd_mzSRW6pZ9up&export=download) | +559 | 2023/09/04 | belzedar_ in discord |
| allwayspawns | [allwayspawns-14b62a6ed6ab.nnue](https://drive.google.com/u/0/uc?id=1qiwQL2lOVqbgTIsqjcePr5ixGJgMxiPL&export=download) | +804 | 2025/07/31 | belzedar_ in discord |
| almost | [almost-39e5d547319b.nnue](https://drive.google.com/u/0/uc?id=1icb5PxWDOtz4wQ1LCCXBPfn1lA2Hgp-5&export=download) | +120 | 2022/04/24 | belzedar_ in discord |
| amazon | [amazon-f87549144bf8.nnue](https://drive.google.com/u/0/uc?id=1lY_V49wnvDQUrS_dRzLaNdmuhCNPbe2K&export=download) | +138 | 2022/04/24 | belzedar_ in discord |
| anti-losalamos | [anti-losalamos-dc7f04e74c1d.nnue](https://drive.google.com/u/0/uc?id=17qJg1YXf02pYKT47VqYZ5v0zq3hCDter&export=download) | +7 | 2025/07/31 | belzedar_ in discord |
| antiantichess | [antiantichess-bf153de922a8.nnue](https://drive.google.com/u/0/uc?id=14yzPGY93Ci5e2ptOiumN2X5dSQa3lD7I&export=download) | +1309 | 2025/07/31 | belzedar_ in discord |
| antiatomic | [antiatomic-b2484472d286.nnue](https://drive.google.com/u/0/uc?id=1G62LG5j88GsnNKLqaCaPbVNXrUUywbAn&export=download) | +812 | 2025/07/31 | belzedar_ in discord |
| antichess | [antichess-dd3cbe53cd4e.nnue](https://drive.google.com/u/0/uc?id=1a6j61utWpCTADQ8k6BBqYMcKjJ5ESdbl&export=download) | +200 | 2024/09/17 | Fabian Fichter |
| antihouse | [antihouse-66adada8e7bb.nnue](https://drive.google.com/u/0/uc?id=1Dfgvp6M4D55aLL1vD8Oeps7jAG_CeQ36&export=download) | +382 | 2025/07/31 | belzedar_ in discord |
| asean | [asean-47ebb2f6be7b.nnue](https://drive.google.com/u/0/uc?id=123GKcbRkAEdOSi6q6tg-qYTuv1dIwEue&export=download) | +505 | 2022/09/12 | belzedar_ in discord |
| ataxx | [ataxx-e631fe1b1b6d.nnue](https://drive.google.com/u/0/uc?id=1RxG06786uZYuY7wCQ6AX5xM4M8SS90p9&export=download) | +202 | 2022/05/30 | belzedar_ in discord |
| atomar  | [atomar-31ef8e2fb4b6.nnue](https://drive.google.com/u/0/uc?id=1ieWTXzdOYHsBWPVdl6_ZFwhsieLyhYgV&export=download) | +407 | 2023/08/28 | belzedar_ in discord |
| atomic  | [atomic-2cf13ff256cc.nnue](https://drive.google.com/u/0/uc?id=1bC7T3iDft8Kbuxlu3Vm2fERxk7cOSoDy&export=download) | +719 | 2022/08/24 | belzedar_ in discord |
| atomicduck  | [atomicduck-8f6b67399559.nnue](https://drive.google.com/u/0/uc?id=1NgBD_Q8MFSWFaV-7pSNtUJ3Q1lCmFzcq&export=download) | +330 | 2023/08/17 | belzedar_ in discord |
| backrank | [backrank-db95f88c50c9.nnue](https://drive.google.com/u/0/uc?id=1xF02gcBh7OJLiAy4apUXdNfgmswsl_7H&export=download) | +1165 | 2022/05/03 | belzedar_ in discord | [Custom defined variant](https://github.com/fairy-stockfish/Fairy-Stockfish/wiki/Variant-configuration#backrank)
| berolina | [berolina-b7130416b32e.nnue](https://drive.google.com/u/0/uc?id=1lEq4igofllbj1DbfHAy5RM1sn2lUhGaX&export=download) | +1069 | 2023/04/02 | belzedar_ in discord |
| blackletter  | [blackletter-ec42c02c7ebf.nnue](https://drive.google.com/u/0/uc?id=1GoXZrl8XDwJjQZLCpn9fLWx-PLXD4m7i&export=download) | +726 | 2025/07/31 | belzedar_ in discord |
| breakthrough  | [breakthrough-b0305d859ae9.nnue](https://drive.google.com/u/0/uc?id=1n78zlt3UqWcn-X9Av6-iW8Ld1AreaKqm&export=download) | +1522 | 2022/05/27 | belzedar_ in discord |
| breakthrough6 | [breakthrough6-c20c60a05bfd.nnue](https://drive.google.com/u/0/uc?id=1i1yrvaEApCC_ymcOb8FWnXJeFf5uD4Uu&export=download) | +355 | 2022/04/24 | mtaktikos#8757 | [6x6 version of Breakthrough](https://github.com/fairy-stockfish/Fairy-Stockfish/wiki/Variant-configuration#6x6-breakthrough)
| breakthrough7 | [breakthrough7-814165729d80.nnue](https://drive.google.com/u/0/uc?id=1zTFMBrM_zrZNBiGHdg7y3hBqA1s6QMN2&export=download) | +604 | 2022/04/24 | mtaktikos#8757 | [7x7 version of Breakthrough](https://github.com/fairy-stockfish/Fairy-Stockfish/wiki/Variant-configuration#7x7-breakthrough)
| buffalo | [buffalo-cfb43daa99e2.nnue](https://drive.google.com/u/0/uc?id=1nPmdTyC5Qqqm0mnaKMitu-yNeAcxeOfd&export=download) | +493 | 2023/05/04 | belzedar_ in discord |
| bughouse  | [bughouse-cd8cceab93fe.nnue](https://drive.google.com/u/0/uc?id=1qZVSzm5G_KRc33YCqmsPM6Ayxo3CI4ME&export=download) | +403 | 2023/01/24 | belzedar_ in discord |
| cambodian |  | |  | | Compatible with makruk networks
| cannonshogi | [cannonshogi-b9b7fc49f641.nnue](https://drive.google.com/u/0/uc?id=1cs3_NXD75SzJDBRzNQoF_TFpOhjpx_kc&export=download) | +400 | 2024/03/24 | autocorr in discord | 
| capablanca  | [capablanca-bb644ef32758.nnue](https://drive.google.com/u/0/uc?id=1FbTMVSE8MA_0hrTTcTm5edYXTH8PItHR&export=download) | +354 | 2022/05/10 | belzedar_ in discord | Also compatible to gothic, embassy, caparandom
| capahouse | [capahouse-727f2d6c8654.nnue](https://drive.google.com/u/0/uc?id=1J1iLiDppvfE-5jGxUSitwFRsEsj4jYvI&export=download) | +484 | 2023/01/24 | belzedar_ in discord | Capablanca + Crazyhouse
| capture | [capture-d1dc2e97a3d8.nnue](https://drive.google.com/u/0/uc?id=1DxWtldVM0TSniPAKzlhAMGYHuZSqpYH7&export=download) | +603 | 2022/07/29 | belzedar_ in discord | [Custom defined variant](https://github.com/fairy-stockfish/Fairy-Stockfish/wiki/Variant-configuration#capture-chess)
| captureall | [captureall-319f16ac33aa.nnue](https://drive.google.com/u/0/uc?id=1hOmgBNrByjXndmgCAA_48_AKwdoeDAHK&export=download) | +154 | 2022/04/24 | belzedar_ in discord | [Custom defined variant](https://github.com/fairy-stockfish/Fairy-Stockfish/wiki/Variant-configuration#capture-all)
| capturethequeen  | [capturethequeen-f37e2a20b279.nnue](https://drive.google.com/u/0/uc?id=12DMB8tZgttNNarvno8X96Cm4v7w6Zphz&export=download) | +182 | 2023/09/04 | belzedar_ in discord |
| castle  | [castle-6f8f06963acb.nnue](https://drive.google.com/u/0/uc?id=1PKh3V93NgLy9Ek8W9orKkLSGrGbzU0uy&export=download) | +264 | 2023/09/19 | belzedar_ in discord |
| caught-in-a-snag  | [caught-in-a-snag-5a34075cdce3.nnue](https://drive.google.com/u/0/uc?id=1Tomv61uh5ujDjDitJPPrsexW_8yCwUbC&export=download) | +1058 | 2023/09/19 | belzedar_ in discord |
| chak | [chak-068cc47e57f2.nnue](https://drive.google.com/u/0/uc?id=1E5JTwSNBOEKvFQyUg4PKl8fCvw94fWpd&export=download) | +2062 | 2022/08/23 | belzedar_ in discord |
| chaturanga  | [chaturanga-1889e98f8d54.nnue](https://drive.google.com/u/0/uc?id=1kqqsa-sY-Azrqe0pFMPNPN2ztIYpg0OA&export=download) | +156 | 2022/04/20 | belzedar_ in discord |
| checkmateless | [checkmateless-e0e30dd72801.nnue](https://drive.google.com/u/0/uc?id=128mxvT10mjNsafggVYL2EyTrQOLLXCv6&export=download) | +735 | 2022/06/03 | belzedar_ in discord | [Custom defined variant](https://github.com/fairy-stockfish/Fairy-Stockfish/wiki/Variant-configuration#checkmateless-chess)
| checkshogi | [checkshogi-63b3bd1987bd.nnue](https://drive.google.com/u/0/uc?id=182JxVnEY0q_bUybwtEbMEWRJwNjJUx0f&export=download) | +700 | 2024/09/10 | Fabian Fichter |
| chennis | [chennis-a800b7f12a4e.nnue](https://drive.google.com/u/0/uc?id=1Ybv8Y8xqMJUkgIDjsGibEzNtdp8p_rkM&export=download) | +471 | 2022/07/21 | belzedar_ in discord |
| chess | [nn-46832cfbead3.nnue](https://tests.stockfishchess.org/api/nn/nn-46832cfbead3.nnue) | +300 | | | Net from official SF
| chessvshp | [chessvshp-ab6490858f72.nnue](https://drive.google.com/u/0/uc?id=1QoOw0_KTNt1p2J0KaTDAK741od_H_uwK&export=download) | +174 | 2022/05/27 | belzedar_ in discord | [Custom defined variant](https://github.com/fairy-stockfish/Fairy-Stockfish/wiki/Variant-configuration#chess-vs-hoppel-poppel)
| coffeehouse | [coffeehouse-382a268a1ce4.nnue](https://drive.google.com/u/0/uc?id=1DU8lI6V5kC_CKPUIgZSjNiq0ij6MnilK&export=download) | +345 | 2025/07/31 | belzedar_ in discord |
| coffeethreecheck | [coffeethreecheck-8701c021f6e4.nnue](https://drive.google.com/u/0/uc?id=145v9OgzN2uPgsDU_WJokwzkwkSU36uBQ&export=download) | +62 | 2025/07/31 | belzedar_ in discord |
| coregal | [coregal-ad18884bdd3d.nnue](https://drive.google.com/u/0/uc?id=1n0NMAj18LLVVB53hn19XPmc07d8a6aPR&export=download) | +265 | 2022/07/31 | belzedar_ in discord |
| courier | [courier-dd4bd1b77c17.nnue](https://drive.google.com/u/0/uc?id=1fL4VOp1n8RH-S3xU63rYbVCgo-oJ-XCm&export=download) | +756 | 2022/09/09 | belzedar_ in discord |
| crazyhouse  | [crazyhouse-8ebf84784ad2.nnue](https://drive.google.com/u/0/uc?id=1nieguR4yCb0BlME-AUhcrFYkmyIOGvqs&export=download) | +1136 | 2022/09/05 | belzedar_ in discord |
| crossderby | [crossderby-41174b43b913.nnue](https://drive.google.com/u/0/uc?id=1O__7xgCG-JguxMyE_hp-9VzaV_4N4SQu&export=download) | +1186 | 2023/04/11 | belzedar_ in discord |
| crossing | [crossing-796ff991bbb5.nnue](https://drive.google.com/u/0/uc?id=1nenleVt6iuwLV-BNCcMRGY9YPo286X6O&export=download) | +571 | 2022/07/31 | belzedar_ in discord | [Custom defined variant](https://github.com/fairy-stockfish/Fairy-Stockfish/wiki/Variant-configuration#crossing)
| crusade | [crusade-d3410e9d8190.nnue](https://drive.google.com/u/0/uc?id=1eXM2Yn-1xYDkBveMvH078TrPpPElMRkm&export=download) | +947 | 2025/07/31 | belzedar_ in discord |
| dobutsu | [dobutsu-9b0989c28462.nnue](https://drive.google.com/u/0/uc?id=114WfouTyr05gbvraeqzRpg5axwQu77A6&export=download) | +30 | 2024/09/17 | Fabian Fichter |
| doublearmy | [doublearmy-ec096e17b49b.nnue](https://drive.google.com/u/0/uc?id=1oLMMqAYPYyFVBbdnpwmACEuJcncdHEUh&export=download) | +392 | 2022/08/01 | belzedar_ in discord | [Custom defined variant](https://github.com/fairy-stockfish/Fairy-Stockfish/wiki/Variant-configuration#double-army)
| dragon | [dragon-38de1d1ced8a.nnue](https://drive.google.com/u/0/uc?id=1o1ikZ08AKFiu7Gc2hsDA2kxhVI8VUX_e&export=download) | +139 | 2022/09/12 | belzedar_ in discord |
| dragon-chess | [dragon-chess-ca99c8d3853b.nnue](https://drive.google.com/u/0/uc?id=1ZrxEmFD4j13j6okp0gCYhx6HBJokLmOT&export=download) | +367 | 2025/07/31 | belzedar_ in discord |
| dragonfly | [dragonfly-f810e661ca8b.nnue](https://drive.google.com/u/0/uc?id=1qaFibACiHYaM9ExdqAr-Y_RGb6HI5zoC&export=download) | +424 | 2022/04/12 | belzedar_ in discord | [Custom defined variant](https://github.com/fairy-stockfish/Fairy-Stockfish/wiki/Variant-configuration#dragonfly-chess)
| duck | [duck-ba21f91f5d81.nnue](https://drive.google.com/u/0/uc?id=18OCEAX2BiioIlW4Eg-YrJxbrujfMUCm7&export=download) | +468 | 2023/01/24 | Mtaktikos#8757 & belzedar_ in discord |
| elimination | [elimination-1c109379396c.nnue](https://drive.google.com/u/0/uc?id=1DW8OI50EEqGCbZUI7J6x6KxbHgkohC0c&export=download) | +1303 | 2023/04/21 | belzedar_ in discord |
| empire | [empire-751feb44316d.nnue](https://drive.google.com/u/0/uc?id=17CvRd9jxeZ21uop8DHhtHnw08hbz-sBI&export=download) | +635 | 2022/05/24 | belzedar_ in discord |
| euroshogi | [euroshogi-bf3218dec3c8.nnue](https://drive.google.com/u/0/uc?id=1YUVgQ_hhtld9SamUnv2dW8nG6iGiyVMW&export=download) | +601 | 2022/07/23 | belzedar_ in discord |
| extinction | [extinction-4c75a5e2850a.nnue](https://drive.google.com/u/0/uc?id=1a4a45Q4V4sXHPJz0pe0r-kAqAmqzDvJr&export=download) | +699 | 2024/09/10 | nishibuya in discord | [14.0 version +863 by belzedar_](https://drive.google.com/u/0/uc?id=1CSaOnPi0Gfo3t9GqC1XTLoXHBG_G8wvK&export=download)
| flipello | [flipello-aed1bd5d741b.nnue](https://drive.google.com/u/0/uc?id=1elo97JNczmeQSyK_YMxw3xmOD9_fWP-C&export=download) | +354 | 2022/06/10 | belzedar_ in discord |
| forward | [forward-656da5c89014.nnue](https://drive.google.com/u/0/uc?id=1llOHXGNpeQUa-6ccyU3GJK8ZuXqZbw8F&export=download) | +870 | 2025/07/31 | belzedar_ in discord |
| gethenian  | [gethenian-04577cdae549.nnue](https://drive.google.com/u/0/uc?id=1tPW4lF9GJPs3EbZirv73VJYbnkZvnLWQ&export=download) | +293 | 2025/07/31 | belzedar_ in discord |
| gorogoroplus | [gorogoroplus-7bc64726c1c1.nnue](https://drive.google.com/u/0/uc?id=1-k87I3fKHrpfbZwEgqDzYVlZivL4emcE&export=download) | +230 | 2022/04/15 | belzedar_ in discord | [Custom defined variant](https://github.com/fairy-stockfish/Fairy-Stockfish/wiki/Variant-configuration#goro-goro-plus)
| grand | [grand-9e13c7b0ed97.nnue](https://drive.google.com/u/0/uc?id=1Q84y9M93IQG3GUr-ibY8NGjJSEnpV3zy&export=download) | +390 | 2022/05/17 | belzedar_ in discord |
| grandhouse | [grandhouse-dd70cad78bc1.nnue](https://drive.google.com/u/0/uc?id=1f9_y4atKvoyj18ofsmutN6bF3uuyEAjq&export=download) | +760 | 2023/08/28 | belzedar_ in discord |
| grasshopper | [grasshopper-2bb252371adf.nnue](https://drive.google.com/u/0/uc?id=1dE7NiNapQ8T3-D4kaak-LxqIjXUWRcaa&export=download) | +2574 | 2022/06/13 | belzedar_ in discord |
| gustav3 | [gustav3-66e1afdd3bfc.nnue](https://drive.google.com/u/0/uc?id=1ByHVgVRGRUOln7ddHuesGqv-GiNdfHMr&export=download) | +408 | 2023/02/03 | belzedar_ in discord |
| hoppelpoppel | [hoppelpoppel-b4f82c3d6e25.nnue](https://drive.google.com/u/0/uc?id=1k0rWMdzh4KL2jdrMcmkV7H4rgaFT-ggU&export=download) | +444 | 2022/08/05 | belzedar_ in discord |
| horde  | [horde-28173ddccabe.nnue](https://drive.google.com/u/0/uc?id=16BQztGqFIS1n_dYtmdfFVE2EexF-KagX&export=download) | +490 | | belzedar_ in discord |
| isolation  | [isolation-e89caf35dd7a.nnue](https://drive.google.com/u/0/uc?id=1lXXhjTJnxTv4PWCSpjzr-0YdXoATsT14&export=download) | +1040 | 2023/02/03 | Mtaktikos#8757 & belzedar_ in discord |
| janggi  | [janggi-4d3de2fee245.nnue](https://drive.google.com/u/0/uc?id=1OFwEmig0_2tZb5tHqtsv0TZD3M2ZUtZR&export=download) | +943 | 2023/03/27 | belzedar_ in discord | also available as [release with built-in NNUE](https://github.com/fairy-stockfish/Fairy-Stockfish-NNUE/releases/tag/janggi-4d3de2fee245)
| jesonmor | [jesonmor-4211b8d73412.nnue](https://drive.google.com/u/0/uc?id=1aYmDWcIG9xmlHKTM6WMI8IKmOSF1hYO6&export=download) | +100 | 2022/08/08 | belzedar_ in discord |
| judkins | [judkins-7af07e4338cb.nnue](https://drive.google.com/u/0/uc?id=1GRsNc1rhes1y7KVHOPrNcj9EVKidugGM&export=download) | +70 | 2024/03/29 | autocorr in discord | 
| kamikazerooks | [kamikazerooks-bd2283cb720a.nnue](https://drive.google.com/u/0/uc?id=1pohX_24grssrnp1zHjKgWRQAEOWNuzOD&export=download) | +1570 | 2022/05/02 | belzedar_ in discord | [Custom defined variant](https://github.com/fairy-stockfish/Fairy-Stockfish/wiki/Variant-configuration#kamikaze-rooks)
| karouk | [karouk-b32b2113c722.nnue](https://drive.google.com/u/0/uc?id=1SIbElgATJE_2xUvt6iJN-Xm7lN7pDzsU&export=download) | +349 | 2022/04/15 | belzedar_ in discord |
| khans | [khans-466a7f4a78f8.nnue](https://drive.google.com/u/0/uc?id=1YMkEeisAq3Fms_cIjnkZWvxW7XrYxeQj&export=download) | +510 | 2024/03/25 | autocorr in discord |
| kinglet | [kinglet-05fb6b8b928e.nnue](https://drive.google.com/u/0/uc?id=1GjWdEKcl1gJbXslZF4i14HauwSlZt6qa&export=download) | +1007 | 2022/09/15 | belzedar_ in discord |
| kingofthehill  | [kingofthehill-978b86d0e6a4.nnue](https://drive.google.com/u/0/uc?id=1x25r_1PgB5XqttkfR494M4rseiIm0BAV&export=download) | +644 | 2022/04/19 | belzedar_ in discord |
| knightmate  | [knightmate-cd61f8401526.nnue](https://drive.google.com/u/0/uc?id=1Z3fAjS5Ea7bzCzUYgsp8Fox-wjZDl3kN&export=download) | +488 | 2022/07/26 | belzedar_ in discord | |
| kyotoshogi | [kyotoshogi-bd1003a29d89.nnue](https://drive.google.com/u/0/uc?id=1vj829y8S_MHJF3YPuJ28O_2o7oSU_yaz&export=download) | +127 | 2022/05/24 | belzedar_ in discord |
| la-mancha-squeez  | [la-mancha-squeez-15935698fea8.nnue](https://drive.google.com/u/0/uc?id=1Q3Wju7-I4EMhaw-CzgGGDugO2hAIlLhO&export=download) | +565 | 2025/07/31 | belzedar_ in discord |
| legan | [legan-70f73b6fda50.nnue](https://drive.google.com/u/0/uc?id=18fozU8LfNP-5LCbBlMv13UN8iC7ww20h&export=download) | +576 | 2023/04/24 | belzedar_ in discord |
| losalamos | [losalamos-4bee7c4fb6d3.nnue](https://drive.google.com/u/0/uc?id=1qeCQINcVbJkXn7eEbHuFKXdpVL-qpzMY&export=download) | +84 | 2022/08/08 | belzedar_ in discord |
| losers  | [losers-3ea1d7d4a61f.nnue](https://drive.google.com/u/0/uc?id=1DgqWen6CkkU6kdyRt4cGfNrUOkP02Bzk&export=download) | +368 | 2022/09/19 | belzedar_ in discord |
| makpong | [makpong-eae03bc9dbf8.nnue](https://drive.google.com/u/0/uc?id=1iIbHaTLDvJLF2HGMEkXs4b_mi2ajqJUU&export=download) | +931 | 2022/04/28 | belzedar_ in discord |
| makruk  | [makruk-a8c621e24a8c.nnue](https://drive.google.com/u/0/uc?id=1jOhdVe1VBZjBaPWO2IYR1_iscyMA0ylW&export=download) | +248 | 2022/09/19 | belzedar_ in discord | also available as [release with built-in NNUE](https://github.com/fairy-stockfish/Fairy-Stockfish-NNUE/releases/tag/makruk-a8c621e24a8c)
| makrukhouse | [makrukhouse-3b28cf864f23.nnue](https://drive.google.com/u/0/uc?id=1C0e8hhhbNzYs1epvKozKOO063wtCdvWI&export=download) | +600 | 2022/09/19 | belzedar_ in discord |
| manchu | [manchu-6e95bcfa334f.nnue](https://drive.google.com/u/0/uc?id=1pTInPVdRXBhK57JhKUqUt9Ebse9Rje26&export=download) | +290 | 2024/09/03 | Fabian Fichter |
| mansindam | [mansindam-dc396c59a74b.nnue](https://drive.google.com/u/0/uc?id=1Q_H1rh-1gaYoT1nE7C16FzVm3abJIggl&export=download) | +441 | 2023/04/21 | belzedar_ in discord |
| massacre | [massacre-06c1f5400bba.nnue](https://drive.google.com/u/0/uc?id=1u1cPi0ffvNe06IPWzQ6vC6DOZJIk88Sq&export=download) | +284 | 2022/04/18 | mtaktikos#8757 | [Custom defined variant](https://github.com/fairy-stockfish/Fairy-Stockfish/wiki/Variant-configuration#massacre-chess)
| minihouse  | [minihouse-d415b4dbfe2c.nnue](https://drive.google.com/u/0/uc?id=19gz3KKtbZuIJfvnWFS99GLamzXW1Pk9N&export=download) | +176 | 2023/09/19 | belzedar_ in discord |
| minishogi  | [minishogi-a8c76af35580.nnue](https://drive.google.com/u/0/uc?id=1JEKzbNfLfq47y7lM9uNqCkGqeRrvfFhh&export=download) | +147 | 2023/07/03 | autocorr & belzedar_ in discord | 1st place in [14th UEC cup](https://github.com/fairy-stockfish/Fairy-Stockfish/wiki/Tournament-results#14th-uec-cup-minishogi-2022)
| minixiangqi | [minixiangqi-12c45d5da817.nnue](https://drive.google.com/u/0/uc?id=1olNzEqMDtqLC7lnt7Rsst39ar1tzsv86&export=download) | +604 | 2022/04/26 | belzedar_ in discord |
| misere | [misere-c488fb592f7b.nnue](https://drive.google.com/u/0/uc?id=169eSjDw_Q-9YplVyDZMCqOFyzy8y2rvN&export=download) | +9 | 2022/06/26 | belzedar_ in discord | [Custom defined variant](https://github.com/fairy-stockfish/Fairy-Stockfish/wiki/Variant-configuration#misere-chess)
| mounted | [mounted-7a5dfe301eaf.nnue](https://drive.google.com/u/0/uc?id=1xjLRsSP0io5yaXS8yY9oANML7o4wA-Ut&export=download) | +297 | 2022/04/15 | belzedar_ in discord | [Custom defined variant](https://github.com/fairy-stockfish/Fairy-Stockfish/wiki/Variant-configuration#mounted)
| newzealand | [newzealand-464a42989876.nnue](https://drive.google.com/u/0/uc?id=11TC1irKBewo25nbqpX2o0tdgQuyrWjMx&export=download) | +359 | 2022/09/20 | belzedar_ in discord |
| nightrider | [nightrider-5086efb80097.nnue](https://drive.google.com/u/0/uc?id=1YEEuEjhzCBEXMw0NPgNxWak7q_35OKSZ&export=download) | +420 | 2022/06/26 | belzedar_ in discord |
| nuclear | [nuclear-1c14657d0d4f.nnue](https://drive.google.com/u/0/uc?id=1SxWxugvlOiw_Fz2gQ-XywGp6QO3zXTpw&export=download) | +156 | 2023/09/04 | belzedar_ in discord |
| omicron | [omicron-01e515951a2d.nnue](https://drive.google.com/u/0/uc?id=15jyKkfyyCzedwc0qZTjeJgdSiGHiId9Z&export=download) | +338 | 2023/02/03 | belzedar_ in discord |
| orda | [orda-ac0af819f3a3.nnue](https://drive.google.com/u/0/uc?id=1jqvVVfxLBklECx14N6aLPnMVf5CZ8iXI&export=download) | +815 | 2022/09/23 | belzedar_ in discord |
| ordamirror | [ordamirror-b432a42e3738.nnue](https://drive.google.com/u/0/uc?id=1Fn1D5bUvgig0kj3xN_T20xKA9aauKQQ0&export=download) | +473 | | belzedar_ in discord |
| pawnback | [pawnback-856713dd34cc.nnue](https://drive.google.com/u/0/uc?id=1y-S_us8RRxBf09I_NB5ErutZ5IdXGQ6o&export=download) | +637 | 2023/04/14 | belzedar_ in discord |
| pawnsideways | [pawnsideways-68b37e5c25b0.nnue](https://drive.google.com/u/0/uc?id=1AvP9VBjZbU02AEcOCqeAy3hJ-Ye3jCt3&export=download) | +1021 | 2023/04/07 | belzedar_ in discord |
| pawnsking  | [pawnsking-3ff6ca784355.nnue](https://drive.google.com/u/0/uc?id=1bSHkRswM6l--oUYA7J48znUsQNO0dZlA&export=download) | +786 | 2025/07/31 | belzedar_ in discord |
| perfect | [perfect-2f1fa62897b6.nnue](https://drive.google.com/u/0/uc?id=1-GYa8EBCaHbYWlaUSVJWzH6nKjeBDZmW&export=download) | +371 | 2025/07/31 | belzedar_ in discord |
| petrified | [petrified-fa7e5810f172.nnue](https://drive.google.com/u/0/uc?id=1AQvihbxa30tQmUxX_0DDWci7AzoAyeja&export=download) | +1029 | 2023/09/19 | belzedar_ in discord |
| placement |  | | | | Compatible with chess (`nn-...`) networks
| racingchess | [racingchess-2d84b5d38001.nnue](https://drive.google.com/u/0/uc?id=1_bm2ZzDBWaCToXyrDhFDyAQ7xvXQPhZw&export=download) | +492 | 2022/04/12 | belzedar_ in discord | [Custom defined variant](https://github.com/fairy-stockfish/Fairy-Stockfish/wiki/Variant-configuration#racing-chess)
| racingkings  | [racingkings-636b95f085e3.nnue](https://drive.google.com/u/0/uc?id=1Tiq8FqSu7eiekE2iaWQzSdJPg-mhvLzJ&export=download) | +374 | 2022/06/13 | belzedar_ in discord |
| rookmate  | [rookmate-628a294ef446.nnue](https://drive.google.com/u/0/uc?id=1EClau9_R2Z7W2SyM1iGmXr2dWHcZWGlx&export=download) | +634 | 2025/07/31 | belzedar_ in discord |
| seirawan  | [seirawan-432c65fe71fc.nnue](https://drive.google.com/u/0/uc?id=1vZfLrkKdO1Sdo__jRPpuvrvvQD_mYsZX&export=download) | +359 | 2022/05/24 | belzedar_ in discord |
| shaolinking | [shaolinking-ad85d8c73ff6.nnue](https://drive.google.com/u/0/uc?id=1Wny8-rirEPar2F2KCXOXyxLmH0gSFSnc&export=download) | +500 | 2024/08/30 | nishibuya in discord | [Custom defined variant](https://github.com/autocorr/pychess-variants/blob/050cbca8a517c6ef50b1a6953e2a231adb06c7ed/variants.ini#L677)
| shako  | [shako-132828f9a311.nnue](https://drive.google.com/u/0/uc?id=1WbV0E5ruRpNQfmLm6m-ue8iP9wb8MZLD&export=download) | +355 | 2022/06/26 | belzedar_ in discord |
| shatar | [shatar-9798d8353f1e.nnue](https://drive.google.com/u/0/uc?id=10DF_Rj8DcGkYjtylbZ4VnHwj8slth0CU&export=download) | +228 | 2022/04/20 | belzedar_ in discord |
| shatranj  | [shatranj-2859a2411c29.nnue](https://drive.google.com/u/0/uc?id=1rexLnBvGkdJYqzhFGQZQ1T8LTbmx0PIV&export=download) | +278 | 2024/09/17 | Fabian Fichter |
| shinobi | [shinobi-5136c71b83bf.nnue](https://drive.google.com/u/0/uc?id=1Gvwkxs_aMP57RDYndxtwNpytyf4xHEAi&export=download) | +790 | 2022/05/10 | belzedar_ in discord | Only compatible with Largeboards binary. |
| shinobiplus | [shinobiplus-3f956bad5d14.nnue](https://drive.google.com/u/0/uc?id=1L5gwtoWyJVJDSRLlqhqxxEmUD2JgqVCb&export=download) | +696 | 2023/06/07 | GemOfLife#3419 | Only compatible with Largeboards binary. |
| shogi  | [shogi-878ca61334a7.nnue](https://drive.google.com/u/0/uc?id=1RA0mstKWi_tH98DVdLGBamEdE8FXiSgB&export=download) | >+1000 | | Fabian Fichter |
| shogun | [shogun-52c778c11e79.nnue](https://drive.google.com/u/0/uc?id=185Z5IY6qE3Mssolj1lKK0cvPR6HZEwXJ&export=download) | +609 | 2022/05/10 | belzedar_ in discord | Only compatible with Largeboards binary. |
| shouse | [shouse-a9ca0fc73863.nnue](https://drive.google.com/u/0/uc?id=1tG1seU2zmLKIlF8IkcAdkejY7aQ_Iad4&export=download) | +372 | 2022/04/18 | belzedar_ in discord | Seirawan + Crazyhouse
| sittuyin | [sittuyin-04ade227fe43.nnue](https://drive.google.com/u/0/uc?id=1eDRLpEZ53kJnycfvNVqdr6KIrPpeBUO1&export=download) | +202 | 2022/09/29 | belzedar_ in discord |
| sixthrank | [sixthrank-a4350d92b723.nnue](https://drive.google.com/u/0/uc?id=1Wb4hX4OxHlSbBXSCKL06YVMt2ODnI1lu&export=download) | +420 | 2022/04/19 | belzedar_ in discord | [Custom defined variant](https://github.com/fairy-stockfish/Fairy-Stockfish/wiki/Variant-configuration#sixth-rank-chess)
| snailtrail  | [snailtrail-bab057618363.nnue](https://drive.google.com/u/0/uc?id=1C3MdAvvn-5WxuJbDd0N6m7xjhnLYpoyp&export=download) | +445 | 2023/02/03 | Mtaktikos#8757 & belzedar_ in discord |
| spartan | [spartan-9dc484a393db.nnue](https://drive.google.com/u/0/uc?id=1jgLPLnW0-reBFmS2oZJXTh-3loYTMLsd&export=download) | +1266 | 2023/03/31 | belzedar_ in discord |
| squatter  | [squatter-598de979f200.nnue](https://drive.google.com/u/0/uc?id=1PAZJ8ZYQmfkiZfJWLRSqtwWqirnKe5CD&export=download) | +1065 | 2025/07/31 | belzedar_ in discord |
| stardust | [stardust-54dc7419ec9e.nnue](https://drive.google.com/u/0/uc?id=1VFwp2OxmdGjgEJw2TrYLuDdzms7PP5Lb&export=download) | +460 | 2022/06/13 | belzedar_ in discord | [Custom defined variant](https://github.com/fairy-stockfish/Fairy-Stockfish/wiki/Variant-configuration#stardust)
| synochess | [synochess-33c625f8ad3e.nnue](https://drive.google.com/u/0/uc?id=1yt6KEx3goaPm3W_OTaUjEPpgJXqIg0A4&export=download) | +166 | 2022/04/22 | Untitled_Entity#5718 | Only compatible with Largeboards binary. |
| threekings | [threekings-c429a67a6578.nnue](https://drive.google.com/u/0/uc?id=1ulE-FrtedYmTabwOHhGx60ag1UbmC6lm&export=download) | +536 | 2022/09/26 | belzedar_ in discord |
| torishogi | [torishogi-436578ceef5b.nnue](https://drive.google.com/u/0/uc?id=1fMJi2IJqSpE4w3qnIdtE3bidBy4sfRc4&export=download) | +834 | 2022/08/08 | belzedar_ in discord |
| torpedo | [torpedo-25da2c94c6cb.nnue](https://drive.google.com/u/0/uc?id=1GQHE3efeHFeu8OqQw98v6md17P_aOXpO&export=download) | +339 | 2023/04/07 | belzedar_ in discord |
| troitzky | [troitzky-3afb0b22136c.nnue](https://drive.google.com/u/0/uc?id=1LV9qDhkYbNu26anpX1oYNPJa1H_21Bvx&export=download) | +573 | 2023/05/04 | belzedar_ in discord |
| twokings2 | [twokings2-7a85df6f13ff.nnue](https://drive.google.com/u/0/uc?id=1ES6d6zkOip--hjDqQxfvgX41W0CfS0Ay&export=download) | +244 | 2022/04/20 | belzedar_ in discord | [Custom defined variant](https://github.com/fairy-stockfish/Fairy-Stockfish/wiki/Variant-configuration#two-kings-2)
| wolf | [wolf-b80c9ac0422f.nnue](https://drive.google.com/u/0/uc?id=1fL6lL45duRBGXTR4yFmIx_qvun0tSXn7&export=download) | +1827 | 2023/04/28 | belzedar_ in discord |
| xiangqi | [xiangqi-aa162e1771e5.nnue](https://drive.google.com/u/0/uc?id=1QvnOcxLejH7cPLngCxgPz4yhvd6S4LDL&export=download) | +889 | 2023/01/24 | Vincentzyx#0477 | also available as [release with built-in NNUE](https://github.com/fairy-stockfish/Fairy-Stockfish-NNUE/releases/tag/xiangqi-aa162e1771e5)
| xiangqihouse | [xiangqihouse-dc5b4560e41c.nnue](https://drive.google.com/u/0/uc?id=1DkyasRcxpt9D5kE8MH4JsZGUDmaS6s44&export=download) | +535 | 2022/06/13 | belzedar_ in discord | Xiangqi + Crazyhouse hybrid variant

When a variant is specified as compatible to networks of a different variant, such as cambodian->makruk, the NNUE network can simply be used with the current name, it does **not** need to be renamed. E.g., `makruk-....nnue` can be directly used for cambodian as well as makruk.
