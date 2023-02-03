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
| 3check  | [3check-313cc226a173.nnue](https://drive.google.com/u/0/uc?id=1r5o5jboZRqND8picxuAbA0VXXMJM1HuS&export=download) | +276 | | Fabian Fichter |
| 5check  |  |  | | | Compatible to 3check networks
| ai-wok | [ai-wok-530fdd028e59.nnue](https://drive.google.com/u/0/uc?id=1x0Yk__LJEU91D0kjyCmdJc0qcf_nYDYU&export=download) | +352 | 2022/04/15 | Belzedar#8832 |
| almost | [almost-39e5d547319b.nnue](https://drive.google.com/u/0/uc?id=1icb5PxWDOtz4wQ1LCCXBPfn1lA2Hgp-5&export=download) | +120 | 2022/04/24 | Belzedar#8832 |
| amazon | [amazon-f87549144bf8.nnue](https://drive.google.com/u/0/uc?id=1lY_V49wnvDQUrS_dRzLaNdmuhCNPbe2K&export=download) | +138 | 2022/04/24 | Belzedar#8832 |
| antichess | [antichess-689c016df8e0.nnue](https://drive.google.com/u/0/uc?id=1SBLSmQmfrsxFHa3ntAhfYXyL3CoVSSL2&export=download) | +80 | 2022/08/24 | Belzedar#8832 |
| asean | [asean-47ebb2f6be7b.nnue](https://drive.google.com/u/0/uc?id=123GKcbRkAEdOSi6q6tg-qYTuv1dIwEue&export=download) | +505 | 2022/09/12 | Belzedar#8832 |
| ataxx | [ataxx-e631fe1b1b6d.nnue](https://drive.google.com/u/0/uc?id=1RxG06786uZYuY7wCQ6AX5xM4M8SS90p9&export=download) | +202 | 2022/05/30 | Belzedar#8832 |
| atomic  | [atomic-2cf13ff256cc.nnue](https://drive.google.com/u/0/uc?id=1bC7T3iDft8Kbuxlu3Vm2fERxk7cOSoDy&export=download) | +719 | 2022/08/24 | Belzedar#8832 |
| backrank | [backrank-db95f88c50c9.nnue](https://drive.google.com/u/0/uc?id=1xF02gcBh7OJLiAy4apUXdNfgmswsl_7H&export=download) | +1165 | 2022/05/03 | Belzedar#8832 | [Custom defined variant](https://github.com/ianfab/Fairy-Stockfish/wiki/Variant-configuration#backrank)
| breakthrough  | [breakthrough-b0305d859ae9.nnue](https://drive.google.com/u/0/uc?id=1n78zlt3UqWcn-X9Av6-iW8Ld1AreaKqm&export=download) | +1522 | 2022/05/27 | Belzedar#8832 |
| breakthrough6 | [breakthrough6-c20c60a05bfd.nnue](https://drive.google.com/u/0/uc?id=1i1yrvaEApCC_ymcOb8FWnXJeFf5uD4Uu&export=download) | +355 | 2022/04/24 | mtaktikos#8757 | [6x6 version of Breakthrough](https://github.com/ianfab/Fairy-Stockfish/wiki/Variant-configuration#6x6-breakthrough)
| breakthrough7 | [breakthrough7-814165729d80.nnue](https://drive.google.com/u/0/uc?id=1zTFMBrM_zrZNBiGHdg7y3hBqA1s6QMN2&export=download) | +604 | 2022/04/24 | mtaktikos#8757 | [7x7 version of Breakthrough](https://github.com/ianfab/Fairy-Stockfish/wiki/Variant-configuration#7x7-breakthrough)
| bughouse  | [bughouse-cd8cceab93fe.nnue](https://drive.google.com/u/0/uc?id=1qZVSzm5G_KRc33YCqmsPM6Ayxo3CI4ME&export=download) | +403 | 2023/01/24 | Belzedar#8832 |
| cambodian |  | |  | | Compatible with makruk networks
| capablanca  | [capablanca-bb644ef32758.nnue](https://drive.google.com/u/0/uc?id=1FbTMVSE8MA_0hrTTcTm5edYXTH8PItHR&export=download) | +354 | 2022/05/10 | Belzedar#8832 | Also compatible to gothic, embassy, caparandom
| capahouse | [capahouse-727f2d6c8654.nnue](https://drive.google.com/u/0/uc?id=1J1iLiDppvfE-5jGxUSitwFRsEsj4jYvI&export=download) | +484 | 2023/01/24 | Belzedar#8832 | Capablanca + Crazyhouse
| capture | [capture-d1dc2e97a3d8.nnue](https://drive.google.com/u/0/uc?id=1DxWtldVM0TSniPAKzlhAMGYHuZSqpYH7&export=download) | +603 | 2022/07/29 | Belzedar#8832 | [Custom defined variant](https://github.com/ianfab/Fairy-Stockfish/wiki/Variant-configuration#capture-chess)
| captureall | [captureall-319f16ac33aa.nnue](https://drive.google.com/u/0/uc?id=1hOmgBNrByjXndmgCAA_48_AKwdoeDAHK&export=download) | +154 | 2022/04/24 | Belzedar#8832 | [Custom defined variant](https://github.com/ianfab/Fairy-Stockfish/wiki/Variant-configuration#capture-all)
| chak | [chak-068cc47e57f2.nnue](https://drive.google.com/u/0/uc?id=1E5JTwSNBOEKvFQyUg4PKl8fCvw94fWpd&export=download) | +2062 | 2022/08/23 | Belzedar#8832 |
| chaturanga  | [chaturanga-1889e98f8d54.nnue](https://drive.google.com/u/0/uc?id=1kqqsa-sY-Azrqe0pFMPNPN2ztIYpg0OA&export=download) | +156 | 2022/04/20 | Belzedar#8832 |
| checkmateless | [checkmateless-e0e30dd72801.nnue](https://drive.google.com/u/0/uc?id=128mxvT10mjNsafggVYL2EyTrQOLLXCv6&export=download) | +735 | 2022/06/03 | Belzedar#8832 | [Custom defined variant](https://github.com/ianfab/Fairy-Stockfish/wiki/Variant-configuration#checkmateless-chess)
| chennis | [chennis-a800b7f12a4e.nnue](https://drive.google.com/u/0/uc?id=1Ybv8Y8xqMJUkgIDjsGibEzNtdp8p_rkM&export=download) | +471 | 2022/07/21 | Belzedar#8832 |
| chess | [nn-46832cfbead3.nnue](https://tests.stockfishchess.org/api/nn/nn-46832cfbead3.nnue) | +300 | | | Net from official SF
| chessvshp | [chessvshp-ab6490858f72.nnue](https://drive.google.com/u/0/uc?id=1QoOw0_KTNt1p2J0KaTDAK741od_H_uwK&export=download) | +174 | 2022/05/27 | Belzedar#8832 | [Custom defined variant](https://github.com/ianfab/Fairy-Stockfish/wiki/Variant-configuration#chess-vs-hoppel-poppel)
| coregal | [coregal-ad18884bdd3d.nnue](https://drive.google.com/u/0/uc?id=1n0NMAj18LLVVB53hn19XPmc07d8a6aPR&export=download) | +265 | 2022/07/31 | Belzedar#8832 |
| courier | [courier-dd4bd1b77c17.nnue](https://drive.google.com/u/0/uc?id=1fL4VOp1n8RH-S3xU63rYbVCgo-oJ-XCm&export=download) | +756 | 2022/09/09 | Belzedar#8832 |
| crazyhouse  | [crazyhouse-8ebf84784ad2.nnue](https://drive.google.com/u/0/uc?id=1nieguR4yCb0BlME-AUhcrFYkmyIOGvqs&export=download) | +1136 | 2022/09/05 | Belzedar#8832 |
| crossing | [crossing-796ff991bbb5.nnue](https://drive.google.com/u/0/uc?id=1nenleVt6iuwLV-BNCcMRGY9YPo286X6O&export=download) | +571 | 2022/07/31 | Belzedar#8832 | [Custom defined variant](https://github.com/ianfab/Fairy-Stockfish/wiki/Variant-configuration#crossing)
| dobutsu | [dobutsu-b69e434ed334.nnue](https://drive.google.com/u/0/uc?id=1RkejB62mrXj9h0QdwT9ABsA2fvNzSPMJ&export=download) | +21 | 2022/05/24 | Belzedar#8832 |
| doublearmy | [doublearmy-ec096e17b49b.nnue](https://drive.google.com/u/0/uc?id=1oLMMqAYPYyFVBbdnpwmACEuJcncdHEUh&export=download) | +392 | 2022/08/01 | Belzedar#8832 | [Custom defined variant](https://github.com/ianfab/Fairy-Stockfish/wiki/Variant-configuration#double-army)
| dragon | [dragon-38de1d1ced8a.nnue](https://drive.google.com/u/0/uc?id=1o1ikZ08AKFiu7Gc2hsDA2kxhVI8VUX_e&export=download) | +139 | 2022/09/12 | Belzedar#8832 |
| dragonfly | [dragonfly-f810e661ca8b.nnue](https://drive.google.com/u/0/uc?id=1qaFibACiHYaM9ExdqAr-Y_RGb6HI5zoC&export=download) | +424 | 2022/04/12 | Belzedar#8832 | [Custom defined variant](https://github.com/ianfab/Fairy-Stockfish/wiki/Variant-configuration#dragonfly-chess)
| duck | [duck-ba21f91f5d81.nnue](https://drive.google.com/u/0/uc?id=18OCEAX2BiioIlW4Eg-YrJxbrujfMUCm7&export=download) | +468 | 2023/01/24 | Mtaktikos#8757 & Belzedar#8832 |
| empire | [empire-751feb44316d.nnue](https://drive.google.com/u/0/uc?id=17CvRd9jxeZ21uop8DHhtHnw08hbz-sBI&export=download) | +635 | 2022/05/24 | Belzedar#8832 |
| euroshogi | [euroshogi-bf3218dec3c8.nnue](https://drive.google.com/u/0/uc?id=1YUVgQ_hhtld9SamUnv2dW8nG6iGiyVMW&export=download) | +601 | 2022/07/23 | Belzedar#8832 |
| extinction | [extinction-a8e86467b370.nnue](https://drive.google.com/u/0/uc?id=1CSaOnPi0Gfo3t9GqC1XTLoXHBG_G8wvK&export=download) | +863 | 2022/07/27 | Belzedar#8832 |
| flipello | [flipello-aed1bd5d741b.nnue](https://drive.google.com/u/0/uc?id=1elo97JNczmeQSyK_YMxw3xmOD9_fWP-C&export=download) | +354 | 2022/06/10 | Belzedar#8832 |
| gorogoroplus | [gorogoroplus-7bc64726c1c1.nnue](https://drive.google.com/u/0/uc?id=1-k87I3fKHrpfbZwEgqDzYVlZivL4emcE&export=download) | +230 | 2022/04/15 | Belzedar#8832 | [Custom defined variant](https://github.com/ianfab/Fairy-Stockfish/wiki/Variant-configuration#goro-goro-plus)
| grand | [grand-9e13c7b0ed97.nnue](https://drive.google.com/u/0/uc?id=1Q84y9M93IQG3GUr-ibY8NGjJSEnpV3zy&export=download) | +390 | 2022/05/17 | Belzedar#8832 |
| grandhouse | [grandhouse-35c216476fc5.nnue](https://drive.google.com/u/0/uc?id=1gxcRdtiUDUdBA0MPFZljlV43TO5eXdPD&export=download) | +360 | 2022/04/21 | Belzedar#8832 |
| grasshopper | [grasshopper-2bb252371adf.nnue](https://drive.google.com/u/0/uc?id=1dE7NiNapQ8T3-D4kaak-LxqIjXUWRcaa&export=download) | +2574 | 2022/06/13 | Belzedar#8832 |
| gustav3 | [gustav3-66e1afdd3bfc.nnue](https://drive.google.com/u/0/uc?id=1ByHVgVRGRUOln7ddHuesGqv-GiNdfHMr&export=download) | +408 | 2023/02/03 | Belzedar#8832 |
| hoppelpoppel | [hoppelpoppel-b4f82c3d6e25.nnue](https://drive.google.com/u/0/uc?id=1k0rWMdzh4KL2jdrMcmkV7H4rgaFT-ggU&export=download) | +444 | 2022/08/05 | Belzedar#8832 |
| horde  | [horde-28173ddccabe.nnue](https://drive.google.com/u/0/uc?id=16BQztGqFIS1n_dYtmdfFVE2EexF-KagX&export=download) | +490 | | Belzedar#8832 |
| janggi  | [janggi-7fb17c3419dc.nnue](https://drive.google.com/u/0/uc?id=1mnfJdVKcEgbTYk9hfgoMBMIoePxv9LMs&export=download) | +858 | 2022/07/17 | Belzedar#8832 | also available as [release with built-in NNUE](https://github.com/fairy-stockfish/Fairy-Stockfish-NNUE/releases/tag/janggi-7fb17c3419dc)
| jesonmor | [jesonmor-4211b8d73412.nnue](https://drive.google.com/u/0/uc?id=1aYmDWcIG9xmlHKTM6WMI8IKmOSF1hYO6&export=download) | +100 | 2022/08/08 | Belzedar#8832 |
| kamikazerooks | [kamikazerooks-bd2283cb720a.nnue](https://drive.google.com/u/0/uc?id=1pohX_24grssrnp1zHjKgWRQAEOWNuzOD&export=download) | +1570 | 2022/05/02 | Belzedar#8832 | [Custom defined variant](https://github.com/ianfab/Fairy-Stockfish/wiki/Variant-configuration#kamikaze-rooks)
| karouk | [karouk-b32b2113c722.nnue](https://drive.google.com/u/0/uc?id=1SIbElgATJE_2xUvt6iJN-Xm7lN7pDzsU&export=download) | +349 | 2022/04/15 | Belzedar#8832 |
| kinglet | [kinglet-05fb6b8b928e.nnue](https://drive.google.com/u/0/uc?id=1GjWdEKcl1gJbXslZF4i14HauwSlZt6qa&export=download) | +1007 | 2022/09/15 | Belzedar#8832 |
| kingofthehill  | [kingofthehill-978b86d0e6a4.nnue](https://drive.google.com/u/0/uc?id=1x25r_1PgB5XqttkfR494M4rseiIm0BAV&export=download) | +644 | 2022/04/19 | Belzedar#8832 |
| knightmate  | [knightmate-cd61f8401526.nnue](https://drive.google.com/u/0/uc?id=1Z3fAjS5Ea7bzCzUYgsp8Fox-wjZDl3kN&export=download) | +488 | 2022/07/26 | Belzedar#8832 | |
| kyotoshogi | [kyotoshogi-bd1003a29d89.nnue](https://drive.google.com/u/0/uc?id=1vj829y8S_MHJF3YPuJ28O_2o7oSU_yaz&export=download) | +127 | 2022/05/24 | Belzedar#8832 |
| losalamos | [losalamos-4bee7c4fb6d3.nnue](https://drive.google.com/u/0/uc?id=1qeCQINcVbJkXn7eEbHuFKXdpVL-qpzMY&export=download) | +84 | 2022/08/08 | Belzedar#8832 |
| losers  | [losers-3ea1d7d4a61f.nnue](https://drive.google.com/u/0/uc?id=1DgqWen6CkkU6kdyRt4cGfNrUOkP02Bzk&export=download) | +368 | 2022/09/19 | Belzedar#8832 |
| makpong | [makpong-eae03bc9dbf8.nnue](https://drive.google.com/u/0/uc?id=1iIbHaTLDvJLF2HGMEkXs4b_mi2ajqJUU&export=download) | +931 | 2022/04/28 | Belzedar#8832 |
| makruk  | [makruk-a8c621e24a8c.nnue](https://drive.google.com/u/0/uc?id=1jOhdVe1VBZjBaPWO2IYR1_iscyMA0ylW&export=download) | +248 | 2022/09/19 | Belzedar#8832 | also available as [release with built-in NNUE](https://github.com/fairy-stockfish/Fairy-Stockfish-NNUE/releases/tag/makruk-a8c621e24a8c)
| makrukhouse | [makrukhouse-3b28cf864f23.nnue](https://drive.google.com/u/0/uc?id=1C0e8hhhbNzYs1epvKozKOO063wtCdvWI&export=download) | +600 | 2022/09/19 | Belzedar#8832 |
| massacre | [massacre-06c1f5400bba.nnue](https://drive.google.com/u/0/uc?id=1u1cPi0ffvNe06IPWzQ6vC6DOZJIk88Sq&export=download) | +284 | 2022/04/18 | mtaktikos#8757 | [Custom defined variant](https://github.com/ianfab/Fairy-Stockfish/wiki/Variant-configuration#massacre-chess)
| minishogi  | [minishogi-42cd5b0df4fe.nnue](https://drive.google.com/u/0/uc?id=1kF2CSHkrHllPvpi_w6LgeU_EObVGoOp9&export=download) | +135 | 2022/04/28 | Belzedar#8832 | 1st place in [14th UEC cup](https://github.com/ianfab/Fairy-Stockfish/wiki/Tournament-results#14th-uec-cup-minishogi-2022)
| minixiangqi | [minixiangqi-12c45d5da817.nnue](https://drive.google.com/u/0/uc?id=1olNzEqMDtqLC7lnt7Rsst39ar1tzsv86&export=download) | +604 | 2022/04/26 | Belzedar#8832 |
| misere | [misere-c488fb592f7b.nnue](https://drive.google.com/u/0/uc?id=169eSjDw_Q-9YplVyDZMCqOFyzy8y2rvN&export=download) | +9 | 2022/06/26 | Belzedar#8832 | [Custom defined variant](https://github.com/ianfab/Fairy-Stockfish/wiki/Variant-configuration#misere-chess)
| mounted | [mounted-7a5dfe301eaf.nnue](https://drive.google.com/u/0/uc?id=1xjLRsSP0io5yaXS8yY9oANML7o4wA-Ut&export=download) | +297 | 2022/04/15 | Belzedar#8832 | [Custom defined variant](https://github.com/ianfab/Fairy-Stockfish/wiki/Variant-configuration#mounted)
| newzealand | [newzealand-464a42989876.nnue](https://drive.google.com/u/0/uc?id=11TC1irKBewo25nbqpX2o0tdgQuyrWjMx&export=download) | +359 | 2022/09/20 | Belzedar#8832 |
| nightrider | [nightrider-5086efb80097.nnue](https://drive.google.com/u/0/uc?id=1YEEuEjhzCBEXMw0NPgNxWak7q_35OKSZ&export=download) | +420 | 2022/06/26 | Belzedar#8832 |
| omicron | [omicron-01e515951a2d.nnue](https://drive.google.com/u/0/uc?id=15jyKkfyyCzedwc0qZTjeJgdSiGHiId9Z&export=download) | +338 | 2023/02/03 | Belzedar#8832 |
| orda | [orda-ac0af819f3a3.nnue](https://drive.google.com/u/0/uc?id=1jqvVVfxLBklECx14N6aLPnMVf5CZ8iXI&export=download) | +815 | 2022/09/23 | Belzedar#8832 |
| ordamirror | [ordamirror-b432a42e3738.nnue](https://drive.google.com/u/0/uc?id=1Fn1D5bUvgig0kj3xN_T20xKA9aauKQQ0&export=download) | +473 | | Belzedar#8832 |
| placement |  | | | | Compatible with chess (`nn-...`) networks
| racingchess | [racingchess-2d84b5d38001.nnue](https://drive.google.com/u/0/uc?id=1_bm2ZzDBWaCToXyrDhFDyAQ7xvXQPhZw&export=download) | +492 | 2022/04/12 | Belzedar#8832 | [Custom defined variant](https://github.com/ianfab/Fairy-Stockfish/wiki/Variant-configuration#racing-chess)
| racingkings  | [racingkings-636b95f085e3.nnue](https://drive.google.com/u/0/uc?id=1Tiq8FqSu7eiekE2iaWQzSdJPg-mhvLzJ&export=download) | +374 | 2022/06/13 | Belzedar#8832 |
| seirawan  | [seirawan-432c65fe71fc.nnue](https://drive.google.com/u/0/uc?id=1vZfLrkKdO1Sdo__jRPpuvrvvQD_mYsZX&export=download) | +359 | 2022/05/24 | Belzedar#8832 |
| shako  | [shako-132828f9a311.nnue](https://drive.google.com/u/0/uc?id=1WbV0E5ruRpNQfmLm6m-ue8iP9wb8MZLD&export=download) | +355 | 2022/06/26 | Belzedar#8832 |
| shatar | [shatar-9798d8353f1e.nnue](https://drive.google.com/u/0/uc?id=10DF_Rj8DcGkYjtylbZ4VnHwj8slth0CU&export=download) | +228 | 2022/04/20 | Belzedar#8832 |
| shatranj  | [shatranj-27f6cf35e3fc.nnue](https://drive.google.com/u/0/uc?id=15LZixqirndspeF9p8HCqIv5cLHf0T0Kx&export=download) | +222 | 2022/04/24 | Belzedar#8832 |
| shinobi | [shinobi-5136c71b83bf.nnue](https://drive.google.com/u/0/uc?id=1Gvwkxs_aMP57RDYndxtwNpytyf4xHEAi&export=download) | +790 | 2022/05/10 | Belzedar#8832 | Only compatible with Largeboards binary. |
| shogi  | [shogi-878ca61334a7.nnue](https://drive.google.com/u/0/uc?id=1RA0mstKWi_tH98DVdLGBamEdE8FXiSgB&export=download) | >+1000 | | Fabian Fichter |
| shogun | [shogun-52c778c11e79.nnue](https://drive.google.com/u/0/uc?id=185Z5IY6qE3Mssolj1lKK0cvPR6HZEwXJ&export=download) | +609 | 2022/05/10 | Belzedar#8832 | Only compatible with Largeboards binary. |
| shouse | [shouse-a9ca0fc73863.nnue](https://drive.google.com/u/0/uc?id=1tG1seU2zmLKIlF8IkcAdkejY7aQ_Iad4&export=download) | +372 | 2022/04/18 | Belzedar#8832 | Seirawan + Crazyhouse
| sittuyin | [sittuyin-04ade227fe43.nnue](https://drive.google.com/u/0/uc?id=1eDRLpEZ53kJnycfvNVqdr6KIrPpeBUO1&export=download) | +202 | 2022/09/29 | Belzedar#8832 |
| sixthrank | [sixthrank-a4350d92b723.nnue](https://drive.google.com/u/0/uc?id=1Wb4hX4OxHlSbBXSCKL06YVMt2ODnI1lu&export=download) | +420 | 2022/04/19 | Belzedar#8832 | [Custom defined variant](https://github.com/ianfab/Fairy-Stockfish/wiki/Variant-configuration#sixth-rank-chess)
| stardust | [stardust-54dc7419ec9e.nnue](https://drive.google.com/u/0/uc?id=1VFwp2OxmdGjgEJw2TrYLuDdzms7PP5Lb&export=download) | +460 | 2022/06/13 | Belzedar#8832 | [Custom defined variant](https://github.com/ianfab/Fairy-Stockfish/wiki/Variant-configuration#stardust)
| synochess | [synochess-33c625f8ad3e.nnue](https://drive.google.com/u/0/uc?id=1yt6KEx3goaPm3W_OTaUjEPpgJXqIg0A4&export=download) | +166 | 2022/04/22 | Untitled_Entity#5718 | Only compatible with Largeboards binary. |
| threekings | [threekings-c429a67a6578.nnue](https://drive.google.com/u/0/uc?id=1ulE-FrtedYmTabwOHhGx60ag1UbmC6lm&export=download) | +536 | 2022/09/26 | Belzedar#8832 |
| torishogi | [torishogi-436578ceef5b.nnue](https://drive.google.com/u/0/uc?id=1fMJi2IJqSpE4w3qnIdtE3bidBy4sfRc4&export=download) | +834 | 2022/08/08 | Belzedar#8832 |
| twokings2 | [twokings2-7a85df6f13ff.nnue](https://drive.google.com/u/0/uc?id=1ES6d6zkOip--hjDqQxfvgX41W0CfS0Ay&export=download) | +244 | 2022/04/20 | Belzedar#8832 | [Custom defined variant](https://github.com/ianfab/Fairy-Stockfish/wiki/Variant-configuration#two-kings-2)
| xiangqi  | [xiangqi-aa162e1771e5.nnue](https://drive.google.com/u/0/uc?id=1QvnOcxLejH7cPLngCxgPz4yhvd6S4LDL&export=download) | +889 | 2023/01/24 | Vincentzyx#0477 | also available as [release with built-in NNUE](https://github.com/fairy-stockfish/Fairy-Stockfish-NNUE/releases/tag/xiangqi-aa162e1771e5)
| xiangqihouse | [xiangqihouse-dc5b4560e41c.nnue](https://drive.google.com/u/0/uc?id=1DkyasRcxpt9D5kE8MH4JsZGUDmaS6s44&export=download) | +535 | 2022/06/13 | Belzedar#8832 | Xiangqi + Crazyhouse hybrid variant.

When a variant is specified as compatible to networks of a different variant, such as cambodian->makruk, the NNUE network can simply be used with the current name, it does **not** need to be renamed. E.g., `makruk-....nnue` can be directly used for cambodian as well as makruk.
