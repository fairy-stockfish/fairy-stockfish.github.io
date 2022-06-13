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
| asean | [asean-88c4f9118f34.nnue](https://drive.google.com/u/0/uc?id=1ChM8AhBafoMeyJJDVTxBs9oJ6uIqcEnX&export=download) | +200 | | Belzedar#8832 |
| ataxx | [ataxx-e631fe1b1b6d.nnue](https://drive.google.com/u/0/uc?id=1RxG06786uZYuY7wCQ6AX5xM4M8SS90p9&export=download) | +202 | 2022/05/30 | Belzedar#8832 |
| atomic  | [atomic-4ecb2067c716.nnue](https://drive.google.com/u/0/uc?id=1j-iHpmx37z88-3agaAM4ZAWh45hUwnJ2&export=download) | +601 | 2022/04/07 | Belzedar#8832 |
| backrank | [backrank-db95f88c50c9.nnue](https://drive.google.com/u/0/uc?id=1xF02gcBh7OJLiAy4apUXdNfgmswsl_7H&export=download) | +1165 | 2022/05/03 | Belzedar#8832 | [Custom defined variant](https://github.com/ianfab/Fairy-Stockfish/wiki/Variant-configuration#backrank)
| breakthrough  | [breakthrough-b0305d859ae9.nnue](https://drive.google.com/u/0/uc?id=1n78zlt3UqWcn-X9Av6-iW8Ld1AreaKqm&export=download) | +1522 | 2022/05/27 | Belzedar#8832 |
| breakthrough6 | [breakthrough6-c20c60a05bfd.nnue](https://drive.google.com/u/0/uc?id=1i1yrvaEApCC_ymcOb8FWnXJeFf5uD4Uu&export=download) | +355 | 2022/04/24 | mtaktikos#8757 | [6x6 version of Breakthrough](https://github.com/ianfab/Fairy-Stockfish/wiki/Variant-configuration#6x6-breakthrough)
| breakthrough7 | [breakthrough7-814165729d80.nnue](https://drive.google.com/u/0/uc?id=1zTFMBrM_zrZNBiGHdg7y3hBqA1s6QMN2&export=download) | +604 | 2022/04/24 | mtaktikos#8757 | [7x7 version of Breakthrough](https://github.com/ianfab/Fairy-Stockfish/wiki/Variant-configuration#7x7-breakthrough)
| bughouse  | [bughouse-a53140c72ba2.nnue](https://drive.google.com/u/0/uc?id=1rWCM32j5GQ0xZS0Ofj0jnQCfeCQGBPKQ&export=download) | +338 | | Fabian Fichter |
| cambodian |  | |  | | Compatible with makruk networks
| capablanca  | [capablanca-bb644ef32758.nnue](https://drive.google.com/u/0/uc?id=1FbTMVSE8MA_0hrTTcTm5edYXTH8PItHR&export=download) | +354 | 2022/05/10 | Belzedar#8832 | Also compatible to gothic, embassy, caparandom
| capahouse | [capahouse-9410dee8f2a3.nnue](https://drive.google.com/u/0/uc?id=1xEHbRv1DBgIGDjQJKjWBb5ccw75Ynshv&export=download) | +100 | 2022/04/18 | mtaktikos#8757 | Capablanca + Crazyhouse
| capture | [capture-492a6ee1f0e2.nnue](https://drive.google.com/u/0/uc?id=1bqGXGfdar6M1KbdIOn83jerDIlIzqmBs&export=download) | +237 | 2022/04/15 | Belzedar#8832 | [Custom defined variant](https://github.com/ianfab/Fairy-Stockfish/wiki/Variant-configuration#capture-chess)
| captureall | [captureall-319f16ac33aa.nnue](https://drive.google.com/u/0/uc?id=1hOmgBNrByjXndmgCAA_48_AKwdoeDAHK&export=download) | +154 | 2022/04/24 | Belzedar#8832 | [Custom defined variant](https://github.com/ianfab/Fairy-Stockfish/wiki/Variant-configuration#capture-all)
| chak | [chak-5886256f7530.nnue](https://drive.google.com/u/0/uc?id=1LKiRbLegUj2hzjed76pnvk0Sd1qBagzJ&export=download) | +1027 | 2022/05/09 | Belzedar#8832 |
| chaturanga  | [chaturanga-1889e98f8d54.nnue](https://drive.google.com/u/0/uc?id=1kqqsa-sY-Azrqe0pFMPNPN2ztIYpg0OA&export=download) | +156 | 2022/04/20 | Belzedar#8832 |
| checkmateless | [checkmateless-e0e30dd72801.nnue](https://drive.google.com/u/0/uc?id=128mxvT10mjNsafggVYL2EyTrQOLLXCv6&export=download) | +735 | 2022/06/03 | Belzedar#8832 | [Custom defined variant](https://github.com/ianfab/Fairy-Stockfish/wiki/Variant-configuration#checkmateless-chess)
| chennis | [chennis-88897e88b42a.nnue](https://drive.google.com/u/0/uc?id=1ELt8LhwSaB_qP9cMq6EHEvO_f4UGHbzy&export=download) | +367 | 2022/04/22 | Belzedar#8832 |
| chess | [nn-46832cfbead3.nnue](https://tests.stockfishchess.org/api/nn/nn-46832cfbead3.nnue) | +300 | | | Net from official SF
| chessvshp | [chessvshp-ab6490858f72.nnue](https://drive.google.com/u/0/uc?id=1QoOw0_KTNt1p2J0KaTDAK741od_H_uwK&export=download) | +174 | 2022/05/27 | Belzedar#8832 | [Custom defined variant](https://github.com/ianfab/Fairy-Stockfish/wiki/Variant-configuration#chess-vs-hoppel-poppel)
| coregal | [coregal-fd05f101ebca.nnue](https://drive.google.com/u/0/uc?id=1dYHcHl4BHxQv_Y2topc61gSswshnY5V5&export=download) | +49 | | Belzedar#8832 |
| courier | [courier-3c1762801b7a.nnue](https://drive.google.com/u/0/uc?id=1vX1CbKhUBWjkHm0V9gdKDzAhbMPKrs-T&export=download) | +54 | | Belzedar#8832 |
| crazyhouse  | [crazyhouse-f9698b65f0cb.nnue](https://drive.google.com/u/0/uc?id=16KjOPa0acPp8EngUJNKgntS7UHIMAI2o&export=download) | +954 | 2022/05/17 | Belzedar#8832 |
| crossing | [crossing-826f9ef7f1ee.nnue](https://drive.google.com/u/0/uc?id=1ur46ZvHatLGR02srAuD6Aw9VwmTafltU&export=download) | +308 | 2022/04/19 | Belzedar#8832 | [Custom defined variant](https://github.com/ianfab/Fairy-Stockfish/wiki/Variant-configuration#crossing)
| dobutsu | [dobutsu-b69e434ed334.nnue](https://drive.google.com/u/0/uc?id=1RkejB62mrXj9h0QdwT9ABsA2fvNzSPMJ&export=download) | +21 | 2022/05/24 | Belzedar#8832 |
| doublearmy | [doublearmy-85e8181920b1.nnue](https://drive.google.com/u/0/uc?id=1CXszbxxS7MJS16xV9tGsuZ-_UrJnDzyn&export=download) | +208 | 2022/04/14 | Belzedar#8832 | [Custom defined variant](https://github.com/ianfab/Fairy-Stockfish/wiki/Variant-configuration#double-army)
| dragonfly | [dragonfly-f810e661ca8b.nnue](https://drive.google.com/u/0/uc?id=1qaFibACiHYaM9ExdqAr-Y_RGb6HI5zoC&export=download) | +424 | 2022/04/12 | Belzedar#8832 | [Custom defined variant](https://github.com/ianfab/Fairy-Stockfish/wiki/Variant-configuration#dragonfly-chess)
| empire | [empire-751feb44316d.nnue](https://drive.google.com/u/0/uc?id=17CvRd9jxeZ21uop8DHhtHnw08hbz-sBI&export=download) | +635 | 2022/05/24 | Belzedar#8832 |
| euroshogi | [euroshogi-19fc87111c01.nnue](https://drive.google.com/u/0/uc?id=1y18kXO2LmPl24Rm0QtgJUmY4K_r-nUcA&export=download) | +367 | | Belzedar#8832 |
| extinction | [extinction-4866c9c5c2b6.nnue](https://drive.google.com/u/0/uc?id=1Z5Tw7_rOn03d_MiTgQMFbflqQdnJVA1x&export=download) | +556 | | Belzedar#8832 | slightly weaker than the now incompatible v1.4 (60 elo). |
| flipello | [flipello-aed1bd5d741b.nnue](https://drive.google.com/u/0/uc?id=1elo97JNczmeQSyK_YMxw3xmOD9_fWP-C&export=download) | +354 | 2022/06/10 | Belzedar#8832 |
| gorogoroplus | [gorogoroplus-7bc64726c1c1.nnue](https://drive.google.com/u/0/uc?id=1-k87I3fKHrpfbZwEgqDzYVlZivL4emcE&export=download) | +230 | 2022/04/15 | Belzedar#8832 | [Custom defined variant](https://github.com/ianfab/Fairy-Stockfish/wiki/Variant-configuration#goro-goro-plus)
| grand | [grand-9e13c7b0ed97.nnue](https://drive.google.com/u/0/uc?id=1Q84y9M93IQG3GUr-ibY8NGjJSEnpV3zy&export=download) | +390 | 2022/05/17 | Belzedar#8832 |
| grandhouse | [grandhouse-35c216476fc5.nnue](https://drive.google.com/u/0/uc?id=1gxcRdtiUDUdBA0MPFZljlV43TO5eXdPD&export=download) | +360 | 2022/04/21 | Belzedar#8832 |
| grasshopper | [grasshopper-d138797fceaf.nnue](https://drive.google.com/u/0/uc?id=1_6lBiA-1AQgRbNslgRSd_gdztkZ2-cmU&export=download) | +229 | | Belzedar#8832 |
| hoppelpoppel | [hoppelpoppel-ca81db235bbe.nnue](https://drive.google.com/u/0/uc?id=13P0Pne-h5zZorckiAvLEwTih1sSOAsBC&export=download) | +223 | 2022/04/07 | Belzedar#8832 |
| horde  | [horde-28173ddccabe.nnue](https://drive.google.com/u/0/uc?id=16BQztGqFIS1n_dYtmdfFVE2EexF-KagX&export=download) | +490 | | Belzedar#8832 |
| janggi  | [janggi-ffbf1d95cea2.nnue](https://drive.google.com/u/0/uc?id=1FBMt_XfXz8YNfcSnrh9X122hhdMGVQpi&export=download) | +449 | | Fabian Fichter | also available as [release with built-in NNUE](https://github.com/fairy-stockfish/Fairy-Stockfish-NNUE/releases/tag/janggi-ffbf1d95cea2)
| jesonmor | [jesonmor-ed9259390055.nnue](https://drive.google.com/u/0/uc?id=1QUhX4Qu_Qo-0RyaPU1tZaA5Kvnm4dhWD&export=download) | +68 | | Belzedar#8832 |
| kamikazerooks | [kamikazerooks-bd2283cb720a.nnue](https://drive.google.com/u/0/uc?id=1pohX_24grssrnp1zHjKgWRQAEOWNuzOD&export=download) | +1570 | 2022/05/02 | Belzedar#8832 | [Custom defined variant](https://github.com/ianfab/Fairy-Stockfish/wiki/Variant-configuration#kamikaze-rooks)
| karouk | [karouk-b32b2113c722.nnue](https://drive.google.com/u/0/uc?id=1SIbElgATJE_2xUvt6iJN-Xm7lN7pDzsU&export=download) | +349 | 2022/04/15 | Belzedar#8832 |
| kinglet | [kinglet-7e7b5aaa851e.nnue](https://drive.google.com/u/0/uc?id=1id95-uZiDCxIO2ywhNzh8X3cvEUlXjmM&export=download) | +127 | | Belzedar#8832 |
| kingofthehill  | [kingofthehill-978b86d0e6a4.nnue](https://drive.google.com/u/0/uc?id=1x25r_1PgB5XqttkfR494M4rseiIm0BAV&export=download) | +644 | 2022/04/19 | Belzedar#8832 |
| knightmate  | [knightmate-79005add86eb.nnue](https://drive.google.com/u/0/uc?id=1kjuWnMV0zFMiPDATo56-4A5fc8YH_4hD&export=download) | +361 | 2022/04/24 | Belzedar#8832 | |
| kyotoshogi | [kyotoshogi-bd1003a29d89.nnue](https://drive.google.com/u/0/uc?id=1vj829y8S_MHJF3YPuJ28O_2o7oSU_yaz&export=download) | +127 | 2022/05/24 | Belzedar#8832 |
| losalamos | [losalamos-dd80f372e2f7.nnue](https://drive.google.com/u/0/uc?id=1_st5a2TOP1WtgG-WeiD5jHBMIKBnfqk0&export=download) | +40 | | Belzedar#8832 |
| losers  | [losers-86d93b2d22a3.nnue](https://drive.google.com/u/0/uc?id=1k1Me13VfhehxW4qAIoVxNj7TwRr4dV_x&export=download) | +321 | | Fabian Fichter |
| makpong | [makpong-eae03bc9dbf8.nnue](https://drive.google.com/u/0/uc?id=1iIbHaTLDvJLF2HGMEkXs4b_mi2ajqJUU&export=download) | +931 | 2022/04/28 | Belzedar#8832 |
| makruk  | [makruk-23def9767554.nnue](https://drive.google.com/u/0/uc?id=1Of6fSzUEUKlu5QosO-1hr5G_YOX9Pq7Z&export=download) | +235 | | Belzedar#8832 | also available as [release with built-in NNUE](https://github.com/fairy-stockfish/Fairy-Stockfish-NNUE/releases/tag/makruk-23def9767554)
| makrukhouse | [makrukhouse-200da8bf0331.nnue](https://drive.google.com/u/0/uc?id=1pSMfM0qAaxwPdTCNZejFvzuD5meRncB1&export=download) | +275 | | Belzedar#8832 |
| massacre | [massacre-06c1f5400bba.nnue](https://drive.google.com/u/0/uc?id=1u1cPi0ffvNe06IPWzQ6vC6DOZJIk88Sq&export=download) | +284 | 2022/04/18 | mtaktikos#8757 | [Custom defined variant](https://github.com/ianfab/Fairy-Stockfish/wiki/Variant-configuration#massacre-chess)
| minishogi  | [minishogi-42cd5b0df4fe.nnue](https://drive.google.com/u/0/uc?id=1kF2CSHkrHllPvpi_w6LgeU_EObVGoOp9&export=download) | +135 | 2022/04/28 | Belzedar#8832 | 1st place in [14th UEC cup](https://github.com/ianfab/Fairy-Stockfish/wiki/Tournament-results#14th-uec-cup-minishogi-2022)
| minixiangqi | [minixiangqi-12c45d5da817.nnue](https://drive.google.com/u/0/uc?id=1olNzEqMDtqLC7lnt7Rsst39ar1tzsv86&export=download) | +604 | 2022/04/26 | Belzedar#8832 |
| misere | [misere-00fa1cd359f9.nnue](https://drive.google.com/u/0/uc?id=1Y9m16_m3Dz1eHH9wtyZnXf6P1yAD5Nkp&export=download) | +7 | 2022/06/10 | Belzedar#8832 | [Custom defined variant](https://github.com/ianfab/Fairy-Stockfish/wiki/Variant-configuration#misere-chess)
| mounted | [mounted-7a5dfe301eaf.nnue](https://drive.google.com/u/0/uc?id=1xjLRsSP0io5yaXS8yY9oANML7o4wA-Ut&export=download) | +297 | 2022/04/15 | Belzedar#8832 | [Custom defined variant](https://github.com/ianfab/Fairy-Stockfish/wiki/Variant-configuration#mounted)
| newzealand | [newzealand-0dab2349cc44.nnue](https://drive.google.com/u/0/uc?id=1HMlzQYxwBqnRXxJiIjH6YRFyEj6_dcBP&export=download) | +147 | | Belzedar#8832 |
| nightrider | [nightrider-797ce077f032.nnue](https://drive.google.com/u/0/uc?id=1QqtLEDpWWS7ohja758BTVe0hYpPFBjiA&export=download) | +158 | | Belzedar#8832 |
| orda | [orda-af8fab8f210b.nnue](https://drive.google.com/u/0/uc?id=1feTfj9CnhHYht-Ij1irQ1PLu6UFhucqd&export=download) | +205 | | Belzedar#8832 |
| ordamirror | [ordamirror-b432a42e3738.nnue](https://drive.google.com/u/0/uc?id=1Fn1D5bUvgig0kj3xN_T20xKA9aauKQQ0&export=download) | +473 | | Belzedar#8832 |
| placement |  | | | | Compatible with chess (`nn-...`) networks
| racingchess | [racingchess-2d84b5d38001.nnue](https://drive.google.com/u/0/uc?id=1_bm2ZzDBWaCToXyrDhFDyAQ7xvXQPhZw&export=download) | +492 | 2022/04/12 | Belzedar#8832 | [Custom defined variant](https://github.com/ianfab/Fairy-Stockfish/wiki/Variant-configuration#racing-chess)
| racingkings  | [racingkings-15714b5ffc15.nnue](https://drive.google.com/u/0/uc?id=1AgFUj6jCSoAIR4nZZT9rR_F7IZq2S7VN&export=download) | +362 | 2022/05/27 | Belzedar#8832 |
| seirawan  | [seirawan-432c65fe71fc.nnue](https://drive.google.com/u/0/uc?id=1vZfLrkKdO1Sdo__jRPpuvrvvQD_mYsZX&export=download) | +359 | 2022/05/24 | Belzedar#8832 |
| shatar | [shatar-9798d8353f1e.nnue](https://drive.google.com/u/0/uc?id=10DF_Rj8DcGkYjtylbZ4VnHwj8slth0CU&export=download) | +228 | 2022/04/20 | Belzedar#8832 |
| shatranj  | [shatranj-27f6cf35e3fc.nnue](https://drive.google.com/u/0/uc?id=15LZixqirndspeF9p8HCqIv5cLHf0T0Kx&export=download) | +222 | 2022/04/24 | Belzedar#8832 |
| shinobi | [shinobi-5136c71b83bf.nnue](https://drive.google.com/u/0/uc?id=1Gvwkxs_aMP57RDYndxtwNpytyf4xHEAi&export=download) | +790 | 2022/05/10 | Belzedar#8832 | Only compatible with Largeboards binary. |
| shogi  | [shogi-878ca61334a7.nnue](https://drive.google.com/u/0/uc?id=1RA0mstKWi_tH98DVdLGBamEdE8FXiSgB&export=download) | >+1000 | | Fabian Fichter |
| shogun | [shogun-52c778c11e79.nnue](https://drive.google.com/u/0/uc?id=185Z5IY6qE3Mssolj1lKK0cvPR6HZEwXJ&export=download) | +609 | 2022/05/10 | Belzedar#8832 | Only compatible with Largeboards binary. |
| shouse | [shouse-a9ca0fc73863.nnue](https://drive.google.com/u/0/uc?id=1tG1seU2zmLKIlF8IkcAdkejY7aQ_Iad4&export=download) | +372 | 2022/04/18 | Belzedar#8832 | Seirawan + Crazyhouse
| sittuyin | [sittuyin-3c3ed74dbe54.nnue](https://drive.google.com/u/0/uc?id=1ddJCD22XqZhkz1VHdrxCy1_OTYYDWf0Y&export=download) | +86 | | Belzedar#8832 |
| sixthrank | [sixthrank-a4350d92b723.nnue](https://drive.google.com/u/0/uc?id=1Wb4hX4OxHlSbBXSCKL06YVMt2ODnI1lu&export=download) | +420 | 2022/04/19 | Belzedar#8832 | [Custom defined variant](https://github.com/ianfab/Fairy-Stockfish/wiki/Variant-configuration#sixth-rank-chess)
| stardust | [stardust-54dc7419ec9e.nnue](https://drive.google.com/u/0/uc?id=1VFwp2OxmdGjgEJw2TrYLuDdzms7PP5Lb&export=download) | +460 | 2022/06/13 | Belzedar#8832 | [Custom defined variant](https://github.com/ianfab/Fairy-Stockfish/wiki/Variant-configuration#stardust)
| synochess | [synochess-33c625f8ad3e.nnue](https://drive.google.com/u/0/uc?id=1yt6KEx3goaPm3W_OTaUjEPpgJXqIg0A4&export=download) | +166 | 2022/04/22 | Untitled_Entity#5718 | Only compatible with Largeboards binary. |
| threekings | [threekings-e72e1eda465f.nnue](https://drive.google.com/u/0/uc?id=1X3SFN_khp_FtLXZ1_148oMWS-kLPoaH1&export=download) | +100 | | Belzedar#8832 |
| torishogi | [torishogi-0c3670e88a63.nnue](https://drive.google.com/u/0/uc?id=12IgQRwjzny6oRTeu_7nZapwHskk1GmZR&export=download) | +368 | | Belzedar#8832 |
| twokings2 | [twokings2-7a85df6f13ff.nnue](https://drive.google.com/u/0/uc?id=1ES6d6zkOip--hjDqQxfvgX41W0CfS0Ay&export=download) | +244 | 2022/04/20 | Belzedar#8832 | [Custom defined variant](https://github.com/ianfab/Fairy-Stockfish/wiki/Variant-configuration#two-kings-2)
| xiangqi  | [xiangqi-6f64c55fcb28.nnue](https://drive.google.com/u/0/uc?id=1PyDW6bgQbvOlnIE_OEcMUNQnJiZSLCAG&export=download) | +640 | 2022/05/10 | Belzedar#8832 | also available as [release with built-in NNUE](https://github.com/fairy-stockfish/Fairy-Stockfish-NNUE/releases/tag/xiangqi-6f64c55fcb28)
| xiangqihouse | [xiangqihouse-dc5b4560e41c.nnue](https://drive.google.com/u/0/uc?id=1DkyasRcxpt9D5kE8MH4JsZGUDmaS6s44&export=download) | +535 | 2022/06/13 | Belzedar#8832 | Xiangqi + Crazyhouse hybrid variant.

When a variant is specified as compatible to networks of a different variant, such as cambodian->makruk, the NNUE network can simply be used with the current name, it does **not** need to be renamed. E.g., `makruk-....nnue` can be directly used for cambodian as well as makruk.
