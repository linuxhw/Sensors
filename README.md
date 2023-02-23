Coolest Computers
=================

This is a project to find coolest computers with minimal average operation
CPU temperature reached and share [lm_sensors](https://github.com/lm-sensors/lm-sensors) reports collected by
Linux users at https://linux-hardware.org.

Everyone can contribute to this repository by uploading probes of their computers
by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Total reports: 308661.

Contents
--------

1. [ About        ](#about)
2. [ Notebooks    ](#notebooks)
3. [ Convertibles ](#convertibles)
4. [ Desktops     ](#desktops)
5. [ All In Ones  ](#all-in-ones)
6. [ Servers      ](#servers)
7. [ Mini Pcs     ](#mini-pcs)
8. [ Tablets      ](#tablets)

About
-----

The structure of the directory is the following:

    {TYPE}/{VENDOR}/{MODEL PREFIX}/{MODEL}/{HWID}

    ( e.g. Notebook/Lenovo/G570/G570 20079/87FB42D5B9E2 )

Notebooks
---------

| MFG                      | Model                                            | Avg Temp | Min Temp | Samples | HWID |
|--------------------------|--------------------------------------------------|----------|----------|---------|------|
| Dell                     | Latitude 2100                                    | 13       | 13       | 1       | [DED7CFD6BA3E](<Notebook/Dell/Latitude/Latitude 2100/DED7CFD6BA3E>) |
| MTC                      |                                                  | 13       | 13       | 1       | [A25B9E2EE857](<Notebook/MTC/Others/Others/A25B9E2EE857>) |
| Acer                     | Nattiling V1.05                                  | 15       | 15       | 1       | [DC93E1C70249](<Notebook/Acer/Aspire/Aspire 5720G/DC93E1C70249>) |
| ASUSTek Computer         | 1002HA                                           | 16.5     | 5        | 2       | [BD7B6017A17B](<Notebook/ASUSTek Computer/1002/1002HA/BD7B6017A17B>) |
| Gigabyte Technology      | B450M DS3H-CF                                    | 16.8     | 16.8     | 1       | [1D888CA2D513](<Notebook/Gigabyte Technology/B450M/B450M DS3H/1D888CA2D513>) |
| Gigabyte Technology      | X570 AORUS PRO WIFI                              | 16.8     | 16.8     | 1       | [95167A21E3B5](<Notebook/Gigabyte Technology/X570/X570 AORUS PRO WIFI/95167A21E3B5>) |
| Matsushita Electric I... | CF-30CAQAXBM                                     | 18       | 18       | 1       | [B7E4BBE32472](<Notebook/Matsushita Electric Industrial/CF-30/CF-30CAQAXBM/B7E4BBE32472>) |
| Packard Bell             | EasyNote MV86                                    | 19       | 19       | 1       | [AB78C903C976](<Notebook/Packard Bell/EasyNote/EasyNote MV85/AB78C903C976>) |
| Lenovo                   | 3000 N200 0769ARS                                | 19.5     | 9        | 2       | [D2FCFC273DBC](<Notebook/Lenovo/3000/3000 N200 0769ARS/D2FCFC273DBC>) |
| ASUSTek Computer         | 1201HAG                                          | 20       | 20       | 1       | [295E307D531B](<Notebook/ASUSTek Computer/1201/1201HAG/295E307D531B>) |
| Celestica                | D4040                                            | 20       | 20       | 1       | [318271924A55](<Notebook/Celestica/D/D4040/318271924A55>) |
| Lenovo                   | IdeaPad Creator 5 16ACH6 82L6                    | 20       | 20       | 1       | [C2D72097AF9F](<Notebook/Lenovo/IdeaPad/IdeaPad Creator 5 16ACH6 82L6/C2D72097AF9F>) |
| Lenovo                   | Rev B 20YM                                       | 20       | 20       | 1       | [C12F7F966ADA](<Notebook/Lenovo/Rev/Rev B 20YM/C12F7F966ADA>) |
| ASUSTek Computer         | 1000HE                                           | 20.8     | 4        | 9       | [D827562CFF54](<Notebook/ASUSTek Computer/1000/1000HE/D827562CFF54>) |
| Hewlett-Packard          | Pavilion mini210                                 | 21       | 21       | 1       | [83E78E91DFE4](<Notebook/Hewlett-Packard/Pavilion/Pavilion mini210/83E78E91DFE4>) |
| Lenovo                   | ThinkPad Mini10 3507A31                          | 21       | 21       | 1       | [EAC15D3F8438](<Notebook/Lenovo/ThinkPad/ThinkPad Mini10 3507A31/EAC15D3F8438>) |
| ASUSTek Computer         | S101                                             | 22       | 22       | 1       | [F105B322913E](<Notebook/ASUSTek Computer/S/S101/F105B322913E>) |
| Compal                   | HEL81C                                           | 22       | 22       | 1       | [A865D66BFC39](<Notebook/Compal/HEL81/HEL81C/A865D66BFC39>) |
| Gateway                  | TC78                                             | 22       | 22       | 1       | [19E22B34B8C6](<Notebook/Gateway/TC/TC78/19E22B34B8C6>) |
| Medion                   | S17405                                           | 22       | 22       | 1       | [E3946751A0AE](<Notebook/Medion/S/S17405/E3946751A0AE>) |
| Acer                     | Aspire 4930                                      | 22.5     | 22       | 2       | [DDEA53079864](<Notebook/Acer/Aspire/Aspire 4930/DDEA53079864>) |
| Acer                     | Aspire 4330 V1.22                                | 23       | 23       | 1       | [58A98CF2F229](<Notebook/Acer/Aspire/Aspire 4330/58A98CF2F229>) |
| Hewlett-Packard          | Pavilion dv6000 (RU700UA#ABL)                    | 23       | 23       | 1       | [1E13E58D4FEB](<Notebook/Hewlett-Packard/Pavilion/Pavilion dv6000/1E13E58D4FEB>) |
| KOHJINSHA                | SX series                                        | 23       | 23       | 1       | [83D40EAD03DE](<Notebook/KOHJINSHA/SX/SX series/83D40EAD03DE>) |
| Malata                   | PC-81005 D0.05T42.2A.08                          | 23       | 23       | 1       | [B60B6B072816](<Notebook/Malata/PC/PC-81005/B60B6B072816>) |
| ASUSTek Computer         | 900A                                             | 24       | 24       | 1       | [5CF2B2A11E8B](<Notebook/ASUSTek Computer/900/900A/5CF2B2A11E8B>) |
| Acer                     | Aspire 4935 V1.02                                | 24       | 24       | 1       | [8A8BD3B2B0AD](<Notebook/Acer/Aspire/Aspire 4935/8A8BD3B2B0AD>) |
| Lenovo                   | B450 1S1680033610187                             | 24       | 24       | 1       | [8218F1C4A477](<Notebook/Lenovo/B450/B450 1S1680033610187/8218F1C4A477>) |
| Lenovo                   | B450 1S16800368100G2                             | 24       | 24       | 1       | [A784483E5354](<Notebook/Lenovo/B450/B450 1S16800368100G2/A784483E5354>) |
| LG Electronics           | R510                                             | 24.5     | 16       | 4       | [494F55FC165F](<Notebook/LG Electronics/R/R510/494F55FC165F>) |
| Acer                     | Aspire 5010                                      | 25       | 25       | 1       | [80290CFF114C](<Notebook/Acer/Aspire/Aspire 5010/80290CFF114C>) |
| Lenovo                   | ThinkPad E14 Gen 2 20T6000SIX                    | 25       | 25       | 1       | [7D36F004C684](<Notebook/Lenovo/ThinkPad/ThinkPad E14 Gen 2 20T6000SIX/7D36F004C684>) |
| Lenovo                   | ThinkPad R61 8934F9U                             | 25       | 25       | 1       | [97F19944E270](<Notebook/Lenovo/ThinkPad/ThinkPad R61 8934F9U/97F19944E270>) |
| Lenovo                   | ThinkPad T400 6475K36                            | 25       | 25       | 1       | [28314B7B980A](<Notebook/Lenovo/ThinkPad/ThinkPad T400 6475K36/28314B7B980A>) |
| Gateway                  | EC14 Series                                      | 26       | 26       | 1       | [D144DD8CBB64](<Notebook/Gateway/EC14/EC14 Series/D144DD8CBB64>) |
| Hewlett-Packard          | Pavilion dv6000 (RR388EA#AKD)                    | 26       | 26       | 1       | [C33FB1270EF8](<Notebook/Hewlett-Packard/Pavilion/Pavilion dv6000/C33FB1270EF8>) |
| Lenovo                   | ThinkPad W500 406138U                            | 26       | 26       | 1       | [67C4DC0F2894](<Notebook/Lenovo/ThinkPad/ThinkPad W500 406138U/67C4DC0F2894>) |
| Quanta                   | TW8/SW8/DW8 TBD                                  | 26       | 25       | 2       | [C367358F229B](<Notebook/Wortmann AG/TW8/TW8-SW8-DW8/C367358F229B>) |
| Fujitsu                  | FMVNU6G1C                                        | 26.8     | 26.8     | 1       | [4906D7A5B3A2](<Notebook/Fujitsu/FMVNU6/FMVNU6G1C/4906D7A5B3A2>) |
| Hewlett-Packard          | 2140                                             | 26.8     | 14       | 6       | [D50343B4C62A](<Notebook/Hewlett-Packard/2140/2140/D50343B4C62A>) |
| ASUSTek Computer         | PRIME Z690-P                                     | 27       | 27       | 1       | [72B8953E3CC1](<Notebook/ASUSTek Computer/PRIME/PRIME Z690-P/72B8953E3CC1>) |
| Lenovo                   | ThinkPad T460s 20FACTO1WW                        | 27       | 27       | 1       | [32E24D886543](<Notebook/Lenovo/ThinkPad/ThinkPad T460s 20FACTO1WW/32E24D886543>) |
| Lenovo                   | ThinkPad X1 Carbon 5th 20HR0013AU                | 27       | 27       | 1       | [23FE4576231A](<Notebook/Lenovo/ThinkPad/ThinkPad X1 Carbon 5th 20HR0013AU/23FE4576231A>) |
| PC Specialist            | TN1-156M                                         | 27       | 27       | 1       | [EFD2011446A7](<Notebook/PC Specialist/TN1/TN1-156M/EFD2011446A7>) |
| ASUSTek Computer         | All Series                                       | 27.3     | 11.6     | 3       | [210E79941327](<Notebook/ASUSTek Computer/All/All Series/210E79941327>) |
| Lenovo                   | ThinkPad E495 20NEA00ACD                         | 28       | 28       | 1       | [AF6659E95F85](<Notebook/Lenovo/ThinkPad/ThinkPad E495 20NEA00ACD/AF6659E95F85>) |
| Lenovo                   | ThinkPad P1 Gen 3 20TJS2F40C                     | 28       | 28       | 1       | [B1CE27E0202F](<Notebook/Lenovo/ThinkPad/ThinkPad P1 Gen 3 20TJS2F40C/B1CE27E0202F>) |
| Lenovo                   | ThinkPad T460s 20FAS0UM00                        | 28       | 28       | 1       | [B430F5463741](<Notebook/Lenovo/ThinkPad/ThinkPad T460s 20FAS0UM00/B430F5463741>) |
| Lenovo                   | ThinkPad T460s 20FAS2M30C                        | 28       | 28       | 1       | [F4B9C9C86458](<Notebook/Lenovo/ThinkPad/ThinkPad T460s 20FAS2M30C/F4B9C9C86458>) |
| Lenovo                   | ThinkPad X1 Carbon 6th 20KGS7Y400                | 28       | 28       | 1       | [9E81D4BE71DD](<Notebook/Lenovo/ThinkPad/ThinkPad X1 Carbon 6th 20KGS7Y400/9E81D4BE71DD>) |
| Hewlett-Packard          | Pavilion TS 14 Sleekbook                         | 28.8     | 28.8     | 1       | [F03D007A0607](<Notebook/Hewlett-Packard/Pavilion/Pavilion TS 14 Sleekbook/F03D007A0607>) |

...

See all reports in the [Notebook](<Notebook>) directory.

Convertibles
------------

| MFG                      | Model                                            | Avg Temp | Min Temp | Samples | HWID |
|--------------------------|--------------------------------------------------|----------|----------|---------|------|
| GEO                      | GeoFlex                                          | 31       | 31       | 1       | [3C11134BBC52](<Convertible/GEO/GeoFlex/GeoFlex/3C11134BBC52>) |
| Lenovo                   | Yoga 510-15ISK 80S8                              | 31       | 31       | 1       | [6BC68DE056DD](<Convertible/Lenovo/Yoga/Yoga 510-15ISK 80S8/6BC68DE056DD>) |
| Hewlett-Packard          | Spectre x360 Conv 15                             | 32       | 32       | 1       | [B57D5A0D8416](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Conv 15/B57D5A0D8416>) |
| Samsung Electronics      | 950QDA                                           | 32       | 32       | 1       | [4D0052A7DCEC](<Convertible/Samsung Electronics/950/950QDA/4D0052A7DCEC>) |
| Hewlett-Packard          | ENVY x360 Convert 15                             | 32.8     | 32.8     | 1       | [8E23590C3F45](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convert 15/8E23590C3F45>) |
| Lenovo                   | ThinkPad X1 Yoga 3rd 20LD002MGE                  | 33       | 33       | 1       | [97DB431B4124](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 3rd 20LD002MGE/97DB431B4124>) |
| Google                   | Nautilus                                         | 34       | 34       | 1       | [9BCA4E575536](<Convertible/Google/Nautilus/Nautilus/9BCA4E575536>) |
| Hewlett-Packard          | Pavilion x360 Convertible 14-cd2xxx              | 34       | 34       | 1       | [46C3480361B5](<Convertible/Hewlett-Packard/Pavilion/Pavilion x360 Convertible 14-cd2xxx/46C3480361B5>) |
| Lenovo                   | ThinkPad Yoga 370 20JJS1JS00                     | 34       | 34       | 1       | [5D09AEB1F1F5](<Convertible/Lenovo/ThinkPad/ThinkPad Yoga 370 20JJS1JS00/5D09AEB1F1F5>) |
| Hewlett-Packard          | Spectre x360 Convertible 15t-eb100               | 34.5     | 34       | 2       | [3FDF5B198BCE](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 15t-eb100/3FDF5B198BCE>) |
| Lenovo                   | ThinkPad L13 Yoga Gen 2 20VLA033CD               | 35       | 35       | 1       | [AB401B2DB734](<Convertible/Lenovo/ThinkPad/ThinkPad L13 Yoga Gen 2 20VLA033CD/AB401B2DB734>) |
| Lenovo                   | ThinkPad X1 Yoga 1st 20FRS55D00                  | 35       | 35       | 1       | [E7FE4AB704AC](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 1st 20FRS55D00/E7FE4AB704AC>) |
| Lenovo                   | ThinkPad X1 Yoga Gen 6 20Y0S2B000                | 35       | 35       | 1       | [31A6CC297C85](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga Gen 6 20Y0S2B000/31A6CC297C85>) |
| Lenovo                   | ThinkPad X380 Yoga 20LJS4FU00                    | 35       | 35       | 1       | [E7B8AFA257D6](<Convertible/Lenovo/ThinkPad/ThinkPad X380 Yoga 20LJS4FU00/E7B8AFA257D6>) |
| Medion                   | S4401 MD61533                                    | 35       | 35       | 1       | [73E822B87E89](<Convertible/Medion/S4401/S4401 MD61533/73E822B87E89>) |
| ASUSTek Computer         | TP203NA                                          | 36       | 36       | 1       | [94C83EC5E8F1](<Convertible/ASUSTek Computer/TP203/TP203NA/94C83EC5E8F1>) |
| Dell                     | Latitude 9430                                    | 36       | 36       | 1       | [DF9A6FDB7A07](<Convertible/Dell/Latitude/Latitude 9430/DF9A6FDB7A07>) |
| Lenovo                   | IdeaPadFlex 5 14IAU7 82R7                        | 36       | 36       | 1       | [F702899C3F97](<Convertible/Lenovo/IdeaPadFlex/IdeaPadFlex 5 14IAU7 82R7/F702899C3F97>) |
| Lenovo                   | ThinkPad X1 Yoga 2nd 20JES3D300                  | 36       | 36       | 1       | [46D5ED35DFC7](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 2nd 20JES3D300/46D5ED35DFC7>) |
| Lenovo                   | ThinkPad X1 Yoga 3rd 20LDS1CG00                  | 36       | 36       | 1       | [3C69EF28289E](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 3rd 20LDS1CG00/3C69EF28289E>) |
| Aquarius                 | NS483                                            | 37       | 37       | 1       | [3AEDCE9F7F96](<Convertible/Aquarius/NS/NS483/3AEDCE9F7F96>) |
| Hewlett-Packard          | Pavilion x360 Convertible 15-br0xx               | 37       | 37       | 1       | [E5A0526E3BA9](<Convertible/Hewlett-Packard/Pavilion/Pavilion x360 Convertible 15-br0xx/E5A0526E3BA9>) |
| Lenovo                   | ThinkPad X1 Yoga 1st 20FQ000RUS                  | 37       | 36       | 2       | [2B548A664D69](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 1st 20FQ000RUS/2B548A664D69>) |
| Lenovo                   | ThinkPad Yoga 260 20FD0021PB                     | 37       | 37       | 1       | [0BE55C628852](<Convertible/Lenovo/ThinkPad/ThinkPad Yoga 260 20FD0021PB/0BE55C628852>) |
| Lenovo                   | ThinkPad Yoga 460 20EM001MUS                     | 37       | 37       | 1       | [7E16C7BB64F9](<Convertible/Lenovo/ThinkPad/ThinkPad Yoga 460 20EM001MUS/7E16C7BB64F9>) |
| Hewlett-Packard          | Pavilion x360 m3 Convertible                     | 37.7     | 28       | 3       | [439EE1C689D7](<Convertible/Hewlett-Packard/Pavilion/Pavilion x360 m3 Convertible/439EE1C689D7>) |
| ASUSTek Computer         | ASUS EXPERTBOOK B3402FBA_B3402FBA                | 38       | 38       | 1       | [C286FFC8CF6D](<Convertible/ASUSTek Computer/ASUS/ASUS EXPERTBOOK B3402FBA_B3402FBA/C286FFC8CF6D>) |
| Acer                     | Spin SP111-32N                                   | 38       | 30       | 5       | [FB7E7F217DA0](<Convertible/Acer/Spin/Spin SP111-32N/FB7E7F217DA0>) |
| Dynabook                 | PORTEGE X30W-J                                   | 38       | 38       | 1       | [9328D9232D1E](<Convertible/Dynabook/PORTEGE/PORTEGE X30W-J/9328D9232D1E>) |
| Irbis                    | NB133                                            | 38       | 38       | 1       | [F6A59531C8F5](<Convertible/Irbis/NB/NB133/F6A59531C8F5>) |
| Lenovo                   | FLEX5 81X2                                       | 38       | 38       | 1       | [BC58D7D0A25F](<Convertible/Lenovo/FLEX5/FLEX5 81X2/BC58D7D0A25F>) |
| Lenovo                   | ThinkPad X1 Carbon 4th 20FRS08T00                | 38       | 38       | 1       | [3A0B7992B26B](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Carbon 4th 20FRS08T00/3A0B7992B26B>) |
| Lenovo                   | ThinkPad X1 Yoga 2nd 20JES5033F                  | 38       | 38       | 1       | [0727C01586E3](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 2nd 20JES5033F/0727C01586E3>) |
| Lenovo                   | ThinkPad X1 Yoga 4th 20QFCT01WW                  | 38       | 38       | 1       | [B3CAC6A17E82](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 4th 20QFCT01WW/B3CAC6A17E82>) |
| Lenovo                   | ThinkPad Yoga 11e 5th Gen 20LM0000UK             | 38       | 38       | 1       | [CEB8936E09DD](<Convertible/Lenovo/ThinkPad/ThinkPad Yoga 11e 5th Gen 20LM0000UK/CEB8936E09DD>) |
| Lenovo                   | ThinkPad Yoga 260 20FD002DUS                     | 38       | 38       | 1       | [BF537A35BAEE](<Convertible/Lenovo/ThinkPad/ThinkPad Yoga 260 20FD002DUS/BF537A35BAEE>) |
| Lenovo                   | ThinkPad Yoga 260 20FES00K00                     | 38       | 38       | 1       | [4BA571CAE04F](<Convertible/Lenovo/ThinkPad/ThinkPad Yoga 260 20FES00K00/4BA571CAE04F>) |
| Lenovo                   | Yoga C740 81TC                                   | 38       | 38       | 1       | [CFCEBFB57511](<Convertible/Lenovo/Yoga/Yoga C740 81TC/CFCEBFB57511>) |
| Universal Exports Gro... | ITL 1161-32                                      | 38       | 38       | 1       | [6D2A74C62926](<Convertible/Universal Exports Group Limited/ITL/ITL 1161-32/6D2A74C62926>) |
| ASUSTek Computer         | ZenBook UX564EI_Q538EI                           | 39       | 39       | 1       | [BB10960A3561](<Convertible/ASUSTek Computer/ZenBook/ZenBook UX564EI_Q538EI/BB10960A3561>) |
| Hewlett-Packard          | Pavilion x360 Convertible 11m-ad0xx              | 39       | 39       | 1       | [FEE3C6E80F94](<Convertible/Hewlett-Packard/Pavilion/Pavilion x360 Convertible 11m-ad0xx/FEE3C6E80F94>) |
| Lenovo                   | IdeaPadFlex 5-1470 81C9                          | 39       | 39       | 1       | [40C539EB35E2](<Convertible/Lenovo/IdeaPadFlex/IdeaPadFlex 5-1470 81C9/40C539EB35E2>) |
| Lenovo                   | ThinkPad X1 Yoga 1st 20FQ002YUS                  | 39       | 39       | 1       | [540E50FF3DD8](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 1st 20FQ002YUS/540E50FF3DD8>) |
| Lenovo                   | ThinkPad X1 Yoga 4th 20QF0026MZ                  | 39       | 39       | 1       | [04E30701D93E](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 4th 20QF0026MZ/04E30701D93E>) |
| Lenovo                   | ThinkPad X13 Yoga Gen 2 20W8002GCD               | 39       | 39       | 1       | [AA2D0076557D](<Convertible/Lenovo/ThinkPad/ThinkPad X13 Yoga Gen 2 20W8002GCD/AA2D0076557D>) |
| Lenovo                   | ThinkPad Yoga 11e 3rd Gen 20G8S0R600             | 39       | 39       | 1       | [8565898C718C](<Convertible/Lenovo/ThinkPad/ThinkPad Yoga 11e 3rd Gen 20G8S0R600/8565898C718C>) |
| Lenovo                   | ThinkPad Yoga 11e 3rd Gen 20GAS00000             | 39       | 39       | 1       | [227AE71A08BD](<Convertible/Lenovo/ThinkPad/ThinkPad Yoga 11e 3rd Gen 20GAS00000/227AE71A08BD>) |
| Medion                   | E3222 MD62450                                    | 39       | 37       | 2       | [B078954A1E6E](<Convertible/Medion/E3222/E3222 MD62450/B078954A1E6E>) |
| Positivo                 | NP11G-ER4                                        | 39       | 39       | 1       | [54EB30588ABE](<Convertible/Positivo/NP11/NP11G-ER4/54EB30588ABE>) |
| UMAX                     | VisionBook 10Wr Tab                              | 39       | 39       | 1       | [66B8D7DC98DD](<Convertible/UMAX/VisionBook/VisionBook 10Wr Tab/66B8D7DC98DD>) |
| Dell                     | Inspiron 7405 2n1                                | 39.5     | 35       | 12      | [5E2278D8683A](<Convertible/Dell/Inspiron/Inspiron 7405 2n1/5E2278D8683A>) |

...

See all reports in the [Convertible](<Convertible>) directory.

Desktops
--------

| MFG                      | Model                                            | Avg Temp | Min Temp | Samples | HWID |
|--------------------------|--------------------------------------------------|----------|----------|---------|------|
| ASUSTek Computer         | A78M-E                                           | 2.9      | 2.9      | 1       | [98CC5EF299A1](<Desktop/ASUSTek Computer/A78/A78M-E/98CC5EF299A1>) |
| Gigabyte Technology      | D510UD                                           | 3        | 3        | 1       | [CD922434E955](<Desktop/Gigabyte Technology/D510/D510UD/CD922434E955>) |
| ASUSTek Computer         | F1A55-M LX3                                      | 3.2      | 3.2      | 1       | [7BDE713A3E73](<Desktop/ASUSTek Computer/F1A55-M/F1A55-M LX3/7BDE713A3E73>) |
| MSI                      | A88XI AC                                         | 3.6      | 3.6      | 1       | [6472030E9C91](<Desktop/MSI/MS/MS-7913/6472030E9C91>) |
| Intel                    | D525MWV AAE93081-301                             | 4        | 4        | 1       | [A2C4DA2C4D25](<Desktop/Intel/D525MWV/D525MWV AAE93081-301/A2C4DA2C4D25>) |
| Acer                     | Veriton M2110G                                   | 4.4      | 4.4      | 1       | [3C51480D6EBC](<Desktop/Acer/Veriton/Veriton M2110G/3C51480D6EBC>) |
| Acer                     | Veriton M200-A55 P21-A1                          | 4.6      | 4.6      | 1       | [90CEC252B9B5](<Desktop/Acer/Veriton/Veriton M200-A55/90CEC252B9B5>) |
| ASRock                   | A75 Pro4                                         | 5.1      | 5.1      | 1       | [96EA4D85CB15](<Desktop/ASRock/A75/A75 Pro4/96EA4D85CB15>) |
| EMAXX TECHNOLOGY         | EMX-A70FM2+iCafe                                 | 5.1      | 5.1      | 1       | [FBA7D8F32657](<Desktop/EMAXX TECHNOLOGY/EMX-A70/EMX-A70FM2+iCafe/FBA7D8F32657>) |
| Colorful Technology      | C.A68M-K PLUS V16                                | 5.6      | 4.2      | 2       | [31EDFA0A8B1B](<Desktop/Colorful Technology/C.A68M-K/C.A68M-K PLUS V16/31EDFA0A8B1B>) |
| Biostar                  | Hi-Fi A75S3                                      | 6.2      | 6.2      | 1       | [D5DC43BDE7C3](<Desktop/Biostar/Hi-Fi/Hi-Fi A75S3/D5DC43BDE7C3>) |
| Biostar                  | A55MD2                                           | 6.4      | 6.4      | 1       | [61938B2AE4D8](<Desktop/Biostar/A55/A55MD2/61938B2AE4D8>) |
| MSI                      | FM2-A85XA-G65                                    | 6.6      | 0.9      | 4       | [C089510FA770](<Desktop/MSI/MS/MS-7793/C089510FA770>) |
| ASRock                   | FM2A78 Pro3+                                     | 7        | 7        | 1       | [B642F48F891E](<Desktop/ASRock/FM2A78/FM2A78 Pro3+/B642F48F891E>) |
| Pegatron                 | IPPPV-DCG                                        | 7        | 7        | 1       | [3AEE44D32F62](<Desktop/Pegatron/IPPPV-DCG/IPPPV-DCG/3AEE44D32F62>) |
| Acer                     | Aspire T3-100                                    | 7.6      | 7.6      | 1       | [B20B3ED582EB](<Desktop/Acer/Aspire/Aspire T3-100/B20B3ED582EB>) |
| Phoenix                  | POULSBO                                          | 8        | 8        | 1       | [8DB35042FD70](<Desktop/Phoenix Technologies/POULSBO/POULSBO/8DB35042FD70>) |
| ASRock                   | FM2A85X Extreme6                                 | 8.4      | 1.5      | 7       | [B0497544223A](<Desktop/ASRock/FM2A85X/FM2A85X Extreme6/B0497544223A>) |
| Gigabyte Technology      | F2A75M-D3H 3x                                    | 8.4      | 8.4      | 1       | [0FED77E762AF](<Desktop/Gigabyte Technology/F2A75M-D3H/F2A75M-D3H 3x/0FED77E762AF>) |
| Biostar                  | Hi-Fi A68U3P                                     | 8.4      | 3.9      | 2       | [8FC1E8CD4179](<Desktop/Biostar/Hi-Fi/Hi-Fi A68U3P/8FC1E8CD4179>) |
| ASRock                   | AM1B-MDH                                         | 8.5      | 8.5      | 1       | [ABB5F01248A1](<Desktop/ASRock/AM1/AM1B-MDH/ABB5F01248A1>) |
| MSI                      | FM2-A85XA-G43                                    | 8.5      | 8.5      | 1       | [278A4A2D898B](<Desktop/MSI/MS/MS-7793/278A4A2D898B>) |
| Foxconn                  | A55MX                                            | 8.7      | 2.4      | 2       | [97DF63CD33A3](<Desktop/Foxconn/A55/A55MX/97DF63CD33A3>) |
| ASRock                   | FM2A75M-HD+                                      | 9.3      | 3.5      | 4       | [A50EAA195A9B](<Desktop/ASRock/FM2/FM2A75M-HD+/A50EAA195A9B>) |
| ASRock                   | FM2A55M-VG3                                      | 9.5      | 6.8      | 2       | [46F13B428DE8](<Desktop/ASRock/FM2/FM2A55M-VG3/46F13B428DE8>) |
| Gigabyte Technology      | F2A68HM-D3H                                      | 9.5      | 8.4      | 2       | [C6C8EACAE3BE](<Desktop/Gigabyte Technology/F2/F2A68HM-D3H/C6C8EACAE3BE>) |
| ASRock                   | FM2A75 Pro4+                                     | 9.5      | 4.6      | 3       | [576402E790CB](<Desktop/ASRock/FM2A75/FM2A75 Pro4+/576402E790CB>) |
| Gigabyte Technology      | F2A88X-D3HP                                      | 9.7      | 1.5      | 4       | [34503CCAADCD](<Desktop/Gigabyte Technology/F2/F2A88X-D3HP/34503CCAADCD>) |
| Gigabyte Technology      | F2A85XM-HD3                                      | 9.8      | 1.4      | 4       | [05125910C4AB](<Desktop/Gigabyte Technology/F2/F2A85XM-HD3/05125910C4AB>) |
| Acer                     | Aspire X3475                                     | 9.9      | 9.9      | 1       | [A9866B693934](<Desktop/Acer/Aspire/Aspire X3475/A9866B693934>) |
| MSI                      | FM2-A85XMA-E35                                   | 9.9      | 9.9      | 1       | [72739DA4E3CB](<Desktop/MSI/MS/MS-7721/72739DA4E3CB>) |
| ASUSTek Computer         | F1A55-M LX PLUS R2.0                             | 10       | 10       | 1       | [9BC11A0041D7](<Desktop/ASUSTek Computer/F1A55-M/F1A55-M LX PLUS R2.0/9BC11A0041D7>) |
| NEC Computers            | SiS650                                           | 10       | 10       | 1       | [7CE5CC095A09](<Desktop/NEC Computers/SiS/SiS650/7CE5CC095A09>) |
| ASUSTek Computer         | F1A55-M LK R2.0                                  | 10.1     | 10.1     | 1       | [BAB5AD1D9D6C](<Desktop/ASUSTek Computer/F1A55-M/F1A55-M LK R2.0/BAB5AD1D9D6C>) |
| ASUSTek Computer         | F2A85-M PRO                                      | 10.3     | 2        | 11      | [B28A381E0856](<Desktop/ASUSTek Computer/F2A85-M/F2A85-M PRO/B28A381E0856>) |
| ASRock                   | FM2A75M-DGS                                      | 10.4     | 1.8      | 15      | [D6E0BDA5E1F5](<Desktop/ASRock/FM2/FM2A75M-DGS/D6E0BDA5E1F5>) |
| Colorful Technology      | C.A68M-BTC YV14                                  | 10.4     | 10.4     | 1       | [22AE777848BF](<Desktop/Colorful Technology/C.A68M-BTC/C.A68M-BTC YV14/22AE777848BF>) |
| MSI                      | A58M-E35                                         | 10.5     | 10.5     | 1       | [3BEC28D749A6](<Desktop/MSI/MS/MS-7721/3BEC28D749A6>) |
| ASRock                   | FM2A55M-HD+                                      | 10.9     | 1.5      | 8       | [3AB7B41BC064](<Desktop/ASRock/FM2/FM2A55M-HD+/3AB7B41BC064>) |
| ASUSTek Computer         | CM1745                                           | 10.9     | 10.9     | 1       | [FCCB2634AE68](<Desktop/ASUSTek Computer/CM/CM1745/FCCB2634AE68>) |
| Gigabyte Technology      | F2A88XM-HD3P                                     | 11       | 1        | 12      | [5EC6EE01D955](<Desktop/Gigabyte Technology/F2/F2A88XM-HD3P/5EC6EE01D955>) |
| ASRock                   | AD425PV3                                         | 11       | 11       | 1       | [2819E8136C36](<Desktop/ASRock/AD425/AD425PV3/2819E8136C36>) |
| ASRock                   | A88M-G                                           | 11.1     | 1.2      | 12      | [E863B456B7FB](<Desktop/ASRock/A88/A88M-G/E863B456B7FB>) |
| ASUSTek Computer         | F2A55                                            | 11.2     | 2        | 11      | [076ABF48448A](<Desktop/ASUSTek Computer/F2/F2A55/076ABF48448A>) |
| ECS                      | A78F2P-M2                                        | 11.2     | 11.2     | 1       | [0B65FFB578D6](<Desktop/ECS/A78/A78F2P-M2/0B65FFB578D6>) |
| MSI                      | A55-G41 PC Mate                                  | 11.2     | 5.6      | 2       | [CCA3761E279F](<Desktop/MSI/MS/MS-7793/CCA3761E279F>) |
| ASRock                   | FM2A88M-HD+                                      | 11.3     | 0.2      | 10      | [9EB0694BA8EE](<Desktop/ASRock/FM2/FM2A88M-HD+/9EB0694BA8EE>) |
| Gigabyte Technology      | F2A88X-UP4                                       | 11.4     | 9.5      | 2       | [E1DB0C7FB210](<Desktop/Gigabyte Technology/F2/F2A88X-UP4/E1DB0C7FB210>) |
| Lenovo                   | 31900059 STD or WIN                              | 11.5     | 9.8      | 3       | [F254E9A594AE](<Desktop/Lenovo/H535/H535 10117/F254E9A594AE>) |
| ASUSTek Computer         | CM1435                                           | 11.6     | 4.2      | 2       | [00DE9268F454](<Desktop/ASUSTek Computer/CM/CM1435/00DE9268F454>) |
| MSI                      | A88XM-E45 V2                                     | 11.6     | 2.6      | 3       | [176E4E4D1DB4](<Desktop/MSI/MS/MS-7721/176E4E4D1DB4>) |

...

See all reports in the [Desktop](<Desktop>) directory.

All In Ones
-----------

| MFG                      | Model                                            | Avg Temp | Min Temp | Samples | HWID |
|--------------------------|--------------------------------------------------|----------|----------|---------|------|
| ASUSTek Computer         | M3400WUA                                         | 10       | 10       | 1       | [C57F5A924964](<All In One/ASUSTek Computer/ASUS/ASUS AIO M3400WUA_M3400WUA/C57F5A924964>) |
| Gigabyte Technology      | MQHUDVI                                          | 10.2     | 10.2     | 1       | [2D59EF3CA1FB](<All In One/Gigabyte Technology/GB-A5/GB-A5DNK-RH/2D59EF3CA1FB>) |
| Lenovo                   | Bantry CRB 31900058 WIN                          | 15.9     | 15.9     | 1       | [7D201658F55F](<All In One/Lenovo/B50-35/B50-35 F0AV0025GE/7D201658F55F>) |
| Dell                     | 0H6C3V A00                                       | 26       | 26       | 1       | [8CA64BC62F5D](<All In One/Dell/Inspiron/Inspiron 3464 AIO/8CA64BC62F5D>) |
| Acer                     | Aspire Z3170                                     | 27.6     | 27.6     | 1       | [C9EA09D8D8E4](<All In One/Acer/Aspire/Aspire Z3170/C9EA09D8D8E4>) |
| Hewlett-Packard          | 8924 0101                                        | 28       | 28       | 1       | [B50333765A75](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One Desktop 24-ca0xxx/B50333765A75>) |
| Hewlett-Packard          | 895F                                             | 28       | 28       | 1       | [3F38BA670890](<All In One/Hewlett-Packard/EliteOne/EliteOne 870 27 inch G9 All-in-One Desktop PC/3F38BA670890>) |
| Hewlett-Packard          | 81B7 1001                                        | 29       | 29       | 1       | [A8C851F3B97E](<All In One/Hewlett-Packard/24/24-b116nz/A8C851F3B97E>) |
| Lenovo                   | ThinkCentre M90z 3429D6U                         | 29       | 29       | 1       | [895BB442B1F1](<All In One/Lenovo/ThinkCentre/ThinkCentre M90z 3429D6U/895BB442B1F1>) |
| Apple                    | Mac-F42786C8 PVT                                 | 29.5     | 18       | 2       | [E2AAF60D224B](<All In One/Apple/iMac4/iMac4,1/E2AAF60D224B>) |
| Lenovo                   | C200 10040                                       | 30       | 30       | 1       | [933BB294784A](<All In One/Lenovo/C200/C200 10040/933BB294784A>) |
| eMachines                | EZ1601                                           | 30       | 30       | 1       | [1BF2838575FF](<All In One/eMachines/EZ/EZ1601/1BF2838575FF>) |
| Acer                     | Aspire Z3100                                     | 30.8     | 29.2     | 3       | [FCB646BE5AA6](<All In One/Acer/Aspire/Aspire Z3100/FCB646BE5AA6>) |
| Apple                    | Mac-CFF7D910A743CAAF iMac20,1                    | 31       | 31       | 1       | [4FE23979BC61](<All In One/Apple/iMac20/iMac20,1/4FE23979BC61>) |
| Dell                     | 0NYCKR A00                                       | 31       | 31       | 1       | [B7D11D1CE42A](<All In One/Dell/Inspiron/Inspiron 5490 AIO/B7D11D1CE42A>) |
| Hewlett-Packard          | 8058                                             | 31       | 24       | 2       | [88A8593E7A87](<All In One/Hewlett-Packard/EliteOne/EliteOne 800 G2 23-in Non-Touch AiO/88A8593E7A87>) |
| Lenovo                   | SHARKBAY NO DPK                                  | 31       | 30       | 2       | [A3C99C221D9B](<All In One/Lenovo/C360/C360 10147/A3C99C221D9B>) |
| Lenovo                   | Gardenia CRB SDK0J40700 WIN 3258031067035        | 31.2     | 31.2     | 1       | [9D08ABAF00CD](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 300-22ACL F0BW000LUS/9D08ABAF00CD>) |
| Acer                     | Aspire Z1620                                     | 32       | 32       | 1       | [19DE00291955](<All In One/Acer/Aspire/Aspire Z1620/19DE00291955>) |
| Lenovo                   | SKYBAY SDK0J40709 WIN 3259590606322              | 32       | 32       | 1       | [D5CDA8546DCD](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 700-24ISH F0BE000TGE/D5CDA8546DCD>) |
| Acidanthera              | Mac-AA95B1DDAB278B95 iMac19,1                    | 32.2     | 20       | 4       | [2E9792DAB2C5](<All In One/Acidanthera/iMac19/iMac19,1/2E9792DAB2C5>) |
| Hewlett-Packard          | 81B7 0100                                        | 32.5     | 30       | 2       | [E57D34FC76F5](<All In One/Hewlett-Packard/24/24-b015a/E57D34FC76F5>) |
| Dell                     | 0290HC A00                                       | 33       | 33       | 1       | [0AE65CC3D6F5](<All In One/Dell/Inspiron/Inspiron 5400 AIO/0AE65CC3D6F5>) |
| Lenovo                   | 3702 SDK0J40700 WIN 3258168184765                | 33       | 33       | 1       | [473FAC896EE8](<All In One/Lenovo/IdeaCentre/IdeaCentre A540-24ICB F0EL002EAU/473FAC896EE8>) |
| Medion                   | BTDD-EAIO                                        | 33       | 33       | 1       | [EAE703BD7B5E](<All In One/Medion/V/V20/EAE703BD7B5E>) |
| ASUSTek Computer         | ZN220IC                                          | 34       | 34       | 1       | [B82F232533F4](<All In One/ASUSTek Computer/ZN220/ZN220IC/B82F232533F4>) |
| Acer                     | Aspire C24-1650                                  | 34       | 31       | 3       | [DA8A3F508342](<All In One/Acer/Aspire/Aspire C24-1650/DA8A3F508342>) |
| Acidanthera              | Mac-BE088AF8C5EB4FA2 iMac18,3                    | 34       | 34       | 1       | [5F24E52E7730](<All In One/Acidanthera/iMac18/iMac18,3/5F24E52E7730>) |
| Dell                     | 00V16R A00                                       | 34       | 34       | 1       | [0570B8EB90B0](<All In One/Dell/Inspiron/Inspiron 24 5415 All-in-One/0570B8EB90B0>) |
| Dell                     | 0Y5J85 X02                                       | 34       | 34       | 1       | [88AAB8E50334](<All In One/Dell/Precision/Precision 5720 AIO/88AAB8E50334>) |
| Hewlett-Packard          | 82A6                                             | 34       | 34       | 1       | [A09511605F07](<All In One/Hewlett-Packard/ProOne/ProOne 400 G3 20.0-in Non-Touch AiO/A09511605F07>) |
| Hewlett-Packard          | 2B1C MVB,A                                       | 34.5     | 25       | 2       | [DD737DCCDFC9](<All In One/Hewlett-Packard/23/23-n010ne/DD737DCCDFC9>) |
| Lenovo                   | 36FE No DPK                                      | 34.5     | 31       | 2       | [C2EFDC33FB5A](<All In One/Lenovo/IdeaCentre/IdeaCentre A340-22IWL F0EB006RRI/C2EFDC33FB5A>) |
| Lenovo                   | Gardenia CRB SDK0J40679 WIN 3273049172451        | 34.6     | 34.6     | 1       | [54235580CC91](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 510-22ASR F0CC000RLD/54235580CC91>) |
| Samsung Electronics      | SDNE-R78BA2-20                                   | 34.6     | 34.6     | 1       | [9A8E67BB1389](<All In One/Samsung Electronics/SUR/SUR40/9A8E67BB1389>) |
| Hewlett-Packard          | 2B26 A01                                         | 34.9     | 34.9     | 1       | [CD7770B0F855](<All In One/Hewlett-Packard/23/23-p132la/CD7770B0F855>) |
|                          | H410I                                            | 35       | 35       | 1       | [B5F33AD6FD39](<All In One/Others/H410/H410I/B5F33AD6FD39>) |
| ASUSTek Computer         | V241IC                                           | 35       | 35       | 1       | [E5032F5E2F89](<All In One/ASUSTek Computer/V241/V241IC/E5032F5E2F89>) |
| Acidanthera              | Mac-81E3E92DD6088272 iMac14,4                    | 35       | 35       | 1       | [E2C69985CC45](<All In One/Acidanthera/iMac14/iMac14,4/E2C69985CC45>) |
| Acidanthera              | Mac-DB15BD556843C820 iMac17,1                    | 35       | 24       | 2       | [9344988EB2C8](<All In One/Acidanthera/iMac17/iMac17,1/9344988EB2C8>) |
| Dell                     | 094MXG A00                                       | 35       | 35       | 1       | [6964667AACEF](<All In One/Dell/Inspiron/Inspiron 3464 AIO/6964667AACEF>) |
| Dell                     | 0WNP26 A00                                       | 35       | 35       | 1       | [64251E8FEE77](<All In One/Dell/Precision/Precision 5720 AIO/64251E8FEE77>) |
| Dell                     | 0XHYJF A01                                       | 35       | 28       | 2       | [41C20B38CD55](<All In One/Dell/Inspiron/Inspiron 23 Model 5348/41C20B38CD55>) |
| Hewlett-Packard          | 805E                                             | 35       | 27       | 2       | [9C57BC957F05](<All In One/Hewlett-Packard/ProOne/ProOne 600 G2 21.5-in Non-Touch AiO/9C57BC957F05>) |
| Hewlett-Packard          | 8063                                             | 35       | 35       | 1       | [DF14E11B9481](<All In One/Hewlett-Packard/ProOne/ProOne 400 G2 20-in Non-Touch AiO/DF14E11B9481>) |
| Intel                    | CRESCENTBAY                                      | 35       | 35       | 1       | [C6854E4F8200](<All In One/DEXP/AIO/AIO/C6854E4F8200>) |
| Lenovo                   | 30BB SDK0J40697 WIN 3305051623287                | 35       | 35       | 1       | [06D6727EEBB9](<All In One/Lenovo/ThinkCentre/ThinkCentre M700z 10F1S04X00/06D6727EEBB9>) |
| Lenovo                   | 3718 SDK0J40700 WIN 3258171834020                | 35       | 35       | 1       | [5F2792F86A32](<All In One/Lenovo/IdeaCentre/IdeaCentre A340-24ICK F0ER00BUIX/5F2792F86A32>) |
| Lenovo                   | FFFF SDK0J40697 WIN 3305310775188                | 35       | 35       | 1       | [3131AC26568F](<All In One/Lenovo/V50a-24IMB/V50a-24IMB 11FJ0026RU/3131AC26568F>) |
| Packard Bell             | ONETWO L5870                                     | 35       | 35       | 1       | [81D086748C89](<All In One/Packard Bell/ONETWO/ONETWO L5870/81D086748C89>) |
| SYS                      | H310CH5-TI                                       | 35       | 35       | 1       | [7D88F60E1D91](<All In One/ICL/RAY/RAY S291.Mi/7D88F60E1D91>) |

...

See all reports in the [All In One](<All In One>) directory.

Servers
-------

| MFG                      | Model                                            | Avg Temp | Min Temp | Samples | HWID |
|--------------------------|--------------------------------------------------|----------|----------|---------|------|
| Compaq                   | ProLiant DL380                                   | 8.3      | 8.3      | 1       | [8D95DB95EAF9](<Server/Compaq/ProLiant/ProLiant DL380/8D95DB95EAF9>) |
| Hewlett-Packard          | ProLiant DL360 G4p                               | 8.3      | 8.3      | 1       | [2EE218248D7E](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G4p/2EE218248D7E>) |
| Dell                     | 0N36HY A09                                       | 14.9     | 14.9     | 1       | [E2B668AC841B](<Server/Dell/PowerEdge/PowerEdge R715/E2B668AC841B>) |
| Dell                     | 0N36HY A06                                       | 16       | 16       | 1       | [2A5132FBBBDB](<Server/Dell/PowerEdge/PowerEdge R715/2A5132FBBBDB>) |
| Hewlett-Packard          | ProLiant DL385p Gen8                             | 16.5     | 16.5     | 1       | [EAADD5928698](<Server/Hewlett-Packard/ProLiant/ProLiant DL385p Gen8/EAADD5928698>) |
| Intel                    | S5520UR E22554-650                               | 17       | 17       | 1       | [4F14B8DE6876](<Server/Intel/S5520/S5520UR/4F14B8DE6876>) |
| Supermicro               | A1SA2-2750F                                      | 21       | 21       | 1       | [64B5066C8E62](<Server/Supermicro/A1/A1SA2-2750F/64B5066C8E62>) |
| Supermicro               | X11SSH-CTF                                       | 21       | 21       | 1       | [06E41BB3C6CC](<Server/Supermicro/Super/Super Server/06E41BB3C6CC>) |
| Dell                     | 0FRVY0 A00                                       | 22       | 22       | 1       | [5B911C7AB359](<Server/Dell/PowerEdge/PowerEdge R230/5B911C7AB359>) |
| Supermicro               | A1SAM-2550F                                      | 22       | 22       | 1       | [B9FD41A2E4E7](<Server/Supermicro/A1/A1SAM-2550F/B9FD41A2E4E7>) |
| Supermicro               | X9DR7/E-LN4F                                     | 22       | 22       | 1       | [2B3F5ABC4DD9](<Server/Supermicro/X9/X9DR7-E-LN4F/2B3F5ABC4DD9>) |
| Supermicro               | H8DCL                                            | 22.1     | 13.9     | 2       | [15FCD7D8671C](<Server/Supermicro/H8/H8DCL/15FCD7D8671C>) |
| Supermicro               | H8DG6/H8DGi                                      | 22.3     | 7.8      | 8       | [BD6275D768E9](<Server/Supermicro/H8/H8DG6-H8DGi/BD6275D768E9>) |
| Supermicro               | H8QGL-6F                                         | 22.6     | 22.6     | 1       | [E3929CBFE2DD](<Server/Supermicro/H8/H8QGL/E3929CBFE2DD>) |
| Dell                     | 0T32V9 A16                                       | 23       | 23       | 1       | [BEB8B2D33731](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731>) |
| Hewlett-Packard          | ProLiant DL585 G7                                | 23       | 23       | 1       | [0239B15EF9C8](<Server/Hewlett-Packard/ProLiant/ProLiant DL585 G7/0239B15EF9C8>) |
| Supermicro               | X9DRFR                                           | 23       | 23       | 1       | [09260C793545](<Server/Supermicro/X9/X9DRFR/09260C793545>) |
| Dell                     | 0VRCY5 A14                                       | 24       | 24       | 1       | [DFE3E8DF0E60](<Server/Dell/OEM-R/OEM-R 720xd/DFE3E8DF0E60>) |
| Dell                     | 0X3D66 A02                                       | 24       | 24       | 1       | [978501070240](<Server/Dell/PowerEdge/PowerEdge R720/978501070240>) |
| Dell                     | PowerEdge R420                                   | 24       | 24       | 1       | [A7B363AFB7C6](<Server/Dell/PowerEdge/PowerEdge R420/A7B363AFB7C6>) |
| Hewlett-Packard          | ProLiant BL685c G7                               | 24       | 24       | 1       | [3F69ABE6ED6B](<Server/Hewlett-Packard/ProLiant/ProLiant BL685c G7/3F69ABE6ED6B>) |
| Intel                    | S1200SP H57533-210                               | 24       | 24       | 1       | [4B4C83B49974](<Server/Intel/S1200/S1200SP/4B4C83B49974>) |
| Intel                    | S5500HCV E40912-458                              | 24       | 24       | 1       | [C7EA7736B171](<Server/Intel/S5500/S5500HCV/C7EA7736B171>) |
| Sun Microsystems         | ASSY,MOTHERBOARD,X4170 501-7917-11               | 24       | 24       | 1       | [38FCB3A1E58B](<Server/Sun Microsystems/Sun/Sun Fire X4270 SERVER/38FCB3A1E58B>) |
| Supermicro               | X9DRG-QF                                         | 24       | 24       | 1       | [F4D212B2EC7C](<Server/Supermicro/X9/X9DRG-QF/F4D212B2EC7C>) |
| Supermicro               | H8QG6                                            | 24.3     | 11.6     | 8       | [539918058863](<Server/Supermicro/H8/H8QG6/539918058863>) |
| Dell                     | 04Y8PT A02                                       | 24.8     | 24.8     | 1       | [C712813E6A35](<Server/Dell/PowerEdge/PowerEdge R815/C712813E6A35>) |
| Dell                     | 0MD99X A07                                       | 25       | 25       | 1       | [6232D14EDFD6](<Server/Dell/PowerEdge/PowerEdge R710/6232D14EDFD6>) |
| Hewlett-Packard          | ProLiant DL385 G2                                | 25       | 25       | 1       | [B4F35EF7E4FD](<Server/Hewlett-Packard/ProLiant/ProLiant DL385 G2/B4F35EF7E4FD>) |
| TYAN Computer            | S8026GM2NRE-HOV-B                                | 25.1     | 25.1     | 1       | [FE17689BECB8](<Server/TYAN Computer/S8026/S8026GM2NRE-HOV-B/FE17689BECB8>) |
| ECS                      | PB02CF                                           | 25.3     | 21       | 3       | [864AAAEC666F](<Server/ECS/LIVA/LIVA Q2/864AAAEC666F>) |
| Lenovo                   | 7X04CTO1WW                                       | 25.3     | 24       | 3       | [2297D1A1A8E2](<Server/Lenovo/ThinkSystem/ThinkSystem SR550 -[7X04CTO1WW]/2297D1A1A8E2>) |
| Supermicro               | B11SPE-CPU-TF                                    | 25.8     | 24       | 10      | [FCC793721E72](<Server/Supermicro/SBI-6119/SBI-6119P-T3N/FCC793721E72>) |
|                          | 0JP31P A14                                       | 26       | 26       | 1       | [025EA12C2DA6](<Server/Others/0JP31P/0JP31P A14/025EA12C2DA6>) |
| Dell                     | 04Y8PT A04                                       | 26       | 26       | 1       | [F97CBF897060](<Server/Dell/PowerEdge/PowerEdge R815/F97CBF897060>) |
| Dell                     | 05KX61 A01                                       | 26       | 26       | 1       | [BBFCC212479F](<Server/Dell/PowerEdge/PowerEdge R210/BBFCC212479F>) |
| Dell                     | 081N4V A01                                       | 26       | 26       | 1       | [C84387B3828B](<Server/Dell/PowerEdge/PowerEdge R220/C84387B3828B>) |
| Dell                     | 0JMK61 A00                                       | 26       | 26       | 1       | [A97F0E3198F7](<Server/Dell/Precision/Precision 7920 Rack/A97F0E3198F7>) |
| Fujitsu                  | D2939-B1 S26361-D2939-B17 WGS08 GS01             | 26       | 26       | 1       | [6E07B32FDA2C](<Server/Fujitsu/PRIMERGY/PRIMERGY RX300 S8/6E07B32FDA2C>) |
| Nokia Solutions and N... | AR-D52B1-C/AF0309.02 31S5BMB00Y0                 | 26       | 26       | 1       | [207E2D41F422](<Server/Nokia Solutions and Networks/AR-S5008/AR-S5008A-5A-AF1294.05/207E2D41F422>) |
| Sun Microsystems         | Ultra20 M2                                       | 26       | 26       | 1       | [23D902832E84](<Server/Sun Microsystems/Ultra20/Ultra20 M2/23D902832E84>) |
| Supermicro               | X11SSH-LN4F                                      | 26       | 26       | 1       | [846C921FF296](<Server/Supermicro/Super/Super Server/846C921FF296>) |
| Dell                     | 072T6D A01                                       | 26.5     | 24       | 2       | [B08360FD5D56](<Server/Dell/PowerEdge/PowerEdge R730/B08360FD5D56>) |
| Hewlett-Packard          | ProLiant DL385 G7                                | 26.5     | 22.5     | 2       | [D005510674A2](<Server/Hewlett-Packard/ProLiant/ProLiant DL385 G7/D005510674A2>) |
| Supermicro               | X11SSM-F                                         | 26.5     | 25       | 2       | [E58401D9CAE3](<Server/Supermicro/Super/Super Server/E58401D9CAE3>) |
| Supermicro               | H8SCM                                            | 26.5     | 23.1     | 4       | [4FE36F650E5D](<Server/Supermicro/H8/H8SCM/4FE36F650E5D>) |
| Supermicro               | H8SGL                                            | 26.8     | 20.8     | 2       | [6F8F11F29CE1](<Server/Supermicro/H8/H8SGL/6F8F11F29CE1>) |
| Supermicro               | H11SSL-NC                                        | 26.8     | 26.8     | 1       | [6D89A72C2222](<Server/Supermicro/H11/H11SSL-NC/6D89A72C2222>) |
| Dell                     | 0MK701 A02                                       | 27       | 27       | 1       | [03A5AD7AC4FD](<Server/Dell/PowerEdge/PowerEdge T320/03A5AD7AC4FD>) |
| Lenovo                   | 7Z73CTO1WW                                       | 27       | 27       | 1       | [7AC016764E14](<Server/Lenovo/ThinkSystem/ThinkSystem SR650 V2/7AC016764E14>) |
| Neousys Technology       | NVS-8108 Rev. A1                                 | 27       | 27       | 1       | [0E8814EA22E8](<Server/Neousys Technology/Nuvo-8108GC/Nuvo-8108GC Series/0E8814EA22E8>) |

...

See all reports in the [Server](<Server>) directory.

Mini Pcs
--------

| MFG                      | Model                                            | Avg Temp | Min Temp | Samples | HWID |
|--------------------------|--------------------------------------------------|----------|----------|---------|------|
| ASUSTek Computer         | PN53                                             | 20       | 20       | 1       | [031C11533068](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN53/031C11533068>) |
| Lenovo                   | 3111 SDK0J40697 WIN 3305155831820                | 20       | 20       | 1       | [4032A8D3845F](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M710q 10MQS2SP00/4032A8D3845F>) |
| ZOTAC                    | ZBOXSD-ID12/ID13                                 | 23.5     | 23       | 2       | [B0D20B765A5A](<Mini Pc/ZOTAC/ZBOXSD-ID12/ZBOXSD-ID12-ID13/B0D20B765A5A>) |
| Intel                    | D425KT AAE93083-400                              | 24       | 24       | 1       | [7852FEDF49E3](<Mini Pc/Intel/D425KT/D425KT AAE93083-400/7852FEDF49E3>) |
| Lenovo                   | Aptio CRB 31900004 STD                           | 24       | 24       | 1       | [0127105F4BF9](<Mini Pc/Lenovo/H500/H500 10156/0127105F4BF9>) |
| Lenovo                   | 3181 NO DPK                                      | 25       | 25       | 1       | [5439510A54DE](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75n 11GWCTO1WW/5439510A54DE>) |
| Lenovo                   | 3307 SDK0J40697 WIN 3305334371138                | 25       | 25       | 1       | [70492AEAC407](<Mini Pc/Lenovo/IdeaCentre/IdeaCentre Mini 5 01IMH05 90Q60000UT/70492AEAC407>) |
| Radiant Systems          | P845                                             | 26.8     | 26.8     | 1       | [6CDD298F6645](<Mini Pc/Radiant Systems/P/P845/6CDD298F6645>) |
| Lenovo                   | 316E SDK0J40697 WIN 3305390703058                | 27       | 27       | 1       | [774B111BA6D0](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M70q 11DUS5WF00/774B111BA6D0>) |
| Lenovo                   | 3181 SDK0J40697 WIN 3305385456162                | 27       | 27       | 1       | [FD1DFF3BA674](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75n 11BS0000IX/FD1DFF3BA674>) |
| Lenovo                   | 3190 SDK0J40697 WIN 3305365787267                | 28.1     | 28.1     | 1       | [BC2F7A3B8A4E](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q Gen 2 11JJ007TUS/BC2F7A3B8A4E>) |
| Intel                    | D425KT AAE93083-401                              | 28.5     | 20       | 2       | [B46E3BBE4DB5](<Mini Pc/Intel/D425KT/D425KT AAE93083-401/B46E3BBE4DB5>) |
| Lenovo                   | 32E4 NOK                                         | 29.4     | 29.4     | 1       | [EFCDDA73E969](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q Gen 2 11JNS02N00/EFCDDA73E969>) |
| Intel                    | NUC11TNBv7 M76890-405                            | 30       | 30       | 1       | [CF66240F29BB](<Mini Pc/Intel Client Systems/NUC11/NUC11TNBv7/CF66240F29BB>) |
| Supermicro               | A1SRi                                            | 30       | 30       | 1       | [F097711C2215](<Mini Pc/Supermicro/A1/A1SAi/F097711C2215>) |
| Lenovo                   | 310B SDK0J40697 WIN 3305099885647                | 31       | 31       | 1       | [F360C35AE270](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M910q 10MUS3JC00/F360C35AE270>) |
| Lenovo                   | 314D NOK                                         | 31       | 31       | 1       | [2D30F94EDBCE](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AJS09D00/2D30F94EDBCE>) |
| Lenovo                   | 3307 NOK                                         | 31       | 31       | 1       | [4106B38F9A0C](<Mini Pc/Lenovo/IdeaCentre/IdeaCentre Mini 5 01IMH05 90Q7002AGF/4106B38F9A0C>) |
| ZOTAC                    | ZBOX-BI320                                       | 31       | 31       | 1       | [C92EA8DE9F21](<Mini Pc/ZOTAC/ZBOX-BI/ZBOX-BI320/C92EA8DE9F21>) |
| Lenovo                   | 3190 SDK0J40697 WIN 3305336123648                | 31.6     | 31.6     | 1       | [67A5CBCEF039](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q Gen 2 11JJS00000/67A5CBCEF039>) |
| Intel                    | NUC5i5RYB H40999-506                             | 32       | 32       | 1       | [F3C826711F44](<Mini Pc/Intel/NUC5i5RYB/NUC5i5RYB H40999-506/F3C826711F44>) |
| Lenovo                   | 3181 SEK0T35577 IOT 4247011762342                | 32       | 32       | 1       | [FFC87206F6D0](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75n 11G4000BCA/FFC87206F6D0>) |
| CSL-Computer             | Mini PC AMD HX90                                 | 32.1     | 32.1     | 1       | [2A9E94391C9D](<Mini Pc/CSL-Computer/Mini/Mini PC AMD HX90/2A9E94391C9D>) |
| Lenovo                   | 3181 SDK0J40697 WIN 3305325933916                | 32.2     | 32.2     | 1       | [8D95E87EDCE7](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75n 11GW000BUS/8D95E87EDCE7>) |
| Hewlett-Packard          | 8755                                             | 33       | 33       | 1       | [1BFEF2E15210](<Mini Pc/Hewlett-Packard/Z2/Z2 Mini G5 Workstation/1BFEF2E15210>) |
| Intel                    | NUC11TNBv5 M11900-404                            | 33       | 33       | 1       | [36C9454DF627](<Mini Pc/Intel Client Systems/NUC11/NUC11TNKv5/36C9454DF627>) |
| Intel                    | NUC5i3MYBE H47781-211                            | 33       | 33       | 1       | [5D59DF48F59F](<Mini Pc/Intel/NUC5i3MYBE/NUC5i3MYBE H47781-211/5D59DF48F59F>) |
| Kontron                  | SMX945                                           | 33       | 33       | 1       | [327FC59121CA](<Mini Pc/Kontron/SMX/SMX945/327FC59121CA>) |
| Lenovo                   | 3135 SDK0J40697 WIN 3305169757863                | 33       | 33       | 1       | [CBDCE5B8563C](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920x 10S10013GE/CBDCE5B8563C>) |
| Intel                    | NUC8CCHB K44767-503                              | 33.3     | 28       | 3       | [6D7DBA663446](<Mini Pc/Intel Client Systems/NUC8/NUC8CCHK/6D7DBA663446>) |
| Hewlett-Packard          | 8267 A01                                         | 34       | 26.6     | 5       | [3CB0BE006F96](<Mini Pc/Hewlett-Packard/t530/t530 Thin Client/3CB0BE006F96>) |
| ZOTAC                    | ZBOX-EN1070 Rev.00                               | 34       | 34       | 1       | [E5E09D14FE5B](<Mini Pc/ZOTAC/ZBOX-EN/ZBOX-EN1070/E5E09D14FE5B>) |
| Lenovo                   | Aptio CRB SDK0F82993 WIN                         | 34.2     | 29       | 4       | [983BAD95395D](<Mini Pc/Lenovo/E50-00/E50-00 90BX0018FR/983BAD95395D>) |
| Intel                    | NUC11TNBv7 K87766-405                            | 34.5     | 33       | 2       | [76F3269078BD](<Mini Pc/Intel Client Systems/NUC11/NUC11TNKv7/76F3269078BD>) |
| Lenovo                   | 3172 NOK                                         | 34.5     | 33       | 2       | [AEAA18AE3FAE](<Mini Pc/Lenovo/ThinkStation/ThinkStation P340 Tiny 30DFCTO1WW/AEAA18AE3FAE>) |
| Hewlett-Packard          | 871A                                             | 34.8     | 28       | 5       | [4C0794A3D051](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 400 G6 Desktop Mini PC/4C0794A3D051>) |
| Intel                    | NUC11DBBi7 M17027-402                            | 35       | 35       | 1       | [E66DF9286413](<Mini Pc/Intel Client Systems/NUC11/NUC11BTMi7/E66DF9286413>) |
| Intel                    | NUC7i3BNB J22859-316                             | 35       | 35       | 1       | [38816580003E](<Mini Pc/Intel/NUC7i3BNB/NUC7i3BNB J22859-316/38816580003E>) |
| Intel                    | NUC7i5DNB J57626-509                             | 35       | 35       | 1       | [9520DB1C59AE](<Mini Pc/Intel Client Systems/NUC7/NUC7i5DNKE/9520DB1C59AE>) |
| Lenovo                   | 310B SDK0J40697 WIN 3305099885650                | 35       | 35       | 1       | [36CE0FA0BCB9](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M910q 10MUS3JC00/36CE0FA0BCB9>) |
| Lenovo                   | 3136 SDK0J40697 WIN 3305135508999                | 35       | 35       | 1       | [69045D1A72A5](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RRS4AY00/69045D1A72A5>) |
| Lenovo                   | 316E SDK0J40697 WIN 3305397402565                | 35       | 35       | 1       | [0FFB51699C72](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M70q 11DUS3N000/0FFB51699C72>) |
| VIT                      | M2400-01                                         | 35       | 35       | 1       | [A98D92D7F768](<Mini Pc/VIT/M2400/M2400-01/A98D92D7F768>) |
| AMI                      | Aptio CRB A                                      | 35.4     | 26.8     | 2       | [6EF054560413](<Mini Pc/NEXCOM/VTC/VTC1010/6EF054560413>) |
| Intel                    | NUC11PABi5 K90634-305                            | 35.5     | 21       | 8       | [C98DA0999950](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi5/C98DA0999950>) |
| Hewlett-Packard          | 872C                                             | 35.9     | 35.9     | 1       | [20C32FFA6ABD](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 805 G6 Desktop Mini PC/20C32FFA6ABD>) |
| ASUSTek Computer         | PN64                                             | 36       | 36       | 1       | [4518070764F2](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN64/4518070764F2>) |
| Hewlett-Packard          | 8952                                             | 36       | 36       | 1       | [9FD935DA3E5B](<Mini Pc/Hewlett-Packard/Elite/Elite Mini 600 G9 Desktop PC/9FD935DA3E5B>) |
| Intel                    | CM11EBC4W M15494-302                             | 36       | 36       | 1       | [E186533BF91D](<Mini Pc/Intel Client Systems/CM11/CM11EBC4W/E186533BF91D>) |
| Intel                    | NUC11PABi7 K90104-303                            | 36       | 36       | 1       | [9F39695F50CE](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi7/9F39695F50CE>) |
| Lenovo                   | 310B NOK                                         | 36       | 36       | 1       | [208459EABC9C](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M910q 10MUS0FQ00/208459EABC9C>) |

...

See all reports in the [Mini Pc](<Mini Pc>) directory.

Tablets
-------

| MFG                      | Model                                            | Avg Temp | Min Temp | Samples | HWID |
|--------------------------|--------------------------------------------------|----------|----------|---------|------|
| Lenovo                   | Yoga Duet IML 2020 82E9                          | 28       | 28       | 1       | [8FFE2F20194E](<Tablet/Lenovo/Yoga/Yoga Duet IML 2020 82E9/8FFE2F20194E>) |
| Lenovo                   | ThinkPad X12 Detachable Gen 1 20UWCTO1WW         | 30       | 30       | 1       | [3B7CEBE290BA](<Tablet/Lenovo/ThinkPad/ThinkPad X12 Detachable Gen 1 20UWCTO1WW/3B7CEBE290BA>) |
| Tactus                   | GeoPad 110                                       | 30       | 30       | 1       | [0F02FAE679C1](<Tablet/Tactus/GeoPad/GeoPad 110/0F02FAE679C1>) |
| Lenovo                   | ThinkPad X1 Tablet 20GHS2TC00                    | 32       | 32       | 1       | [E970600EAC8D](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet 20GHS2TC00/E970600EAC8D>) |
| Lenovo                   | ThinkPad X1 Tablet Gen 3 20KJ0010US              | 32       | 32       | 1       | [A3C0804D3B42](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KJ0010US/A3C0804D3B42>) |
| Acer                     | Switch SA5-271                                   | 35.8     | 27       | 4       | [879DB3E2920A](<Tablet/Acer/Switch/Switch SA5-271/879DB3E2920A>) |
| Xplore                   | iX125R1                                          | 36       | 36       | 1       | [274246FD2564](<Tablet/Xplore/iX125/iX125R1/274246FD2564>) |
| Kogan                    | KAL11D600PA                                      | 37       | 37       | 1       | [29024B380C2E](<Tablet/Kogan/KAL11/KAL11D600PA/29024B380C2E>) |
| Lenovo                   | MIX 320 80XF                                     | 37       | 37       | 1       | [430F4094ABA6](<Tablet/Lenovo/MIX/MIX 320 80XF/430F4094ABA6>) |
| Getac                    | K120G2                                           | 38       | 38       | 1       | [9B90212BD0E9](<Tablet/Getac/K120/K120G2/9B90212BD0E9>) |
| Intel                    | Braswell Platform                                | 38       | 38       | 1       | [1E35D60EBB32](<Tablet/Intel/Braswell/Braswell Platform/1E35D60EBB32>) |
| LG Electronics           | 15U340-L.BK55P1                                  | 38       | 38       | 1       | [96572D02BF5F](<Tablet/LG Electronics/15U340/15U340-L.BK55P1/96572D02BF5F>) |
| Lenovo                   | ThinkPad X1 Tablet 20GHCTO1WW                    | 38       | 38       | 1       | [70707A835AE8](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet 20GHCTO1WW/70707A835AE8>) |
| Microsoft                | Surface Pro 8                                    | 38       | 36       | 2       | [3B7494C849C9](<Tablet/Microsoft/Surface/Surface Pro 8/3B7494C849C9>) |
| Prowise                  | PT301                                            | 38       | 38       | 1       | [F09A61A46176](<Tablet/Prowise/PT/PT301/F09A61A46176>) |
| Microsoft                | Surface Pro 6                                    | 38.4     | 25       | 27      | [3CB187ED34B6](<Tablet/Microsoft/Surface/Surface Pro 6/3CB187ED34B6>) |
| Microsoft                | Surface Laptop 4                                 | 38.5     | 33.8     | 4       | [6FFF009110F6](<Tablet/Microsoft/Surface/Surface Laptop 4/6FFF009110F6>) |
| AWOW                     | Book10-N34                                       | 39       | 39       | 1       | [9B4FB389420C](<Tablet/AWOW/Book10/Book10-N34/9B4FB389420C>) |
| Lenovo                   | ThinkPad X12 Detachable Gen 1 20UW0012US         | 39       | 39       | 1       | [54EC26A86D12](<Tablet/Lenovo/ThinkPad/ThinkPad X12 Detachable Gen 1 20UW0012US/54EC26A86D12>) |
| Wortmann AG              | 1220551_1470050                                  | 39       | 39       | 1       | [DF8208081742](<Tablet/Wortmann AG/1220551/1220551_1470050/DF8208081742>) |
| Hewlett-Packard          | Tablet 11m-be0xxx                                | 39.3     | 35       | 3       | [2E8A7FC48C75](<Tablet/Hewlett-Packard/Tablet/Tablet 11m-be0xxx/2E8A7FC48C75>) |
| Microsoft                | Surface Laptop Studio                            | 39.3     | 32       | 3       | [AD9CE584B5E1](<Tablet/Microsoft/Surface/Surface Laptop Studio/AD9CE584B5E1>) |
| AYADEVICE                | AYA NEO 2021                                     | 39.5     | 39.5     | 1       | [A5A12A40B9F5](<Tablet/AYADEVICE/AYA/AYA NEO 2021/A5A12A40B9F5>) |
| Hampoo                   | I1D6_C189_2051                                   | 39.5     | 31       | 2       | [E6AD3027D2BA](<Tablet/Hampoo/I1/I1D6_C189_2051/E6AD3027D2BA>) |
| Getac                    | UX10G2                                           | 40       | 40       | 1       | [9B2D92B11BC9](<Tablet/Getac/UX10/UX10G2/9B2D92B11BC9>) |
| Lenovo                   | ThinkPad 8 20BN002DUK                            | 40       | 40       | 1       | [137482CF53B0](<Tablet/Lenovo/ThinkPad/ThinkPad 8 20BN002DUK/137482CF53B0>) |
| Acer                     | Switch SW312-31                                  | 40.4     | 35       | 8       | [CF3EE8EE1AD4](<Tablet/Acer/Switch/Switch SW312-31/CF3EE8EE1AD4>) |
| Digma                    | CITI E200                                        | 41       | 41       | 1       | [04497C05CA10](<Tablet/Digma/CITI/CITI E200/04497C05CA10>) |
| LG Electronics           | 15U340-LT1FK                                     | 41       | 41       | 1       | [D2FBFE78AD3E](<Tablet/LG Electronics/15U340/15U340-LT1FK/D2FBFE78AD3E>) |
| Microsoft                | Surface Pro 7+                                   | 41       | 41       | 1       | [B513B8EA5A0E](<Tablet/Microsoft/Surface/Surface Pro 7+/B513B8EA5A0E>) |
| Teclast                  | X80 Pro                                          | 41       | 41       | 1       | [315A8B780CB5](<Tablet/Teclast/X80/X80 Pro/315A8B780CB5>) |
| AVITA                    | WT9T12C44T6                                      | 42       | 42       | 1       | [711D0B5CBCED](<Tablet/AVITA/WT9/WT9T12C44T6/711D0B5CBCED>) |
| CAKE                     | POS V3                                           | 42       | 42       | 1       | [6B0F662D72A6](<Tablet/CAKE/POS/POS V3/6B0F662D72A6>) |
| Lenovo                   | ThinkPad Helix 2nd 20CHS16301                    | 42       | 42       | 1       | [BCBFC647A0BF](<Tablet/Lenovo/ThinkPad/ThinkPad Helix 2nd 20CHS16301/BCBFC647A0BF>) |
| Lenovo                   | ThinkPad X1 Tablet 20GGS02600                    | 42       | 42       | 1       | [E0C95B0360EB](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet 20GGS02600/E0C95B0360EB>) |
| Lenovo                   | ThinkPad X1 Tablet Gen 3 20KKS0KE00              | 42       | 42       | 1       | [82D1404D7FE6](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KKS0KE00/82D1404D7FE6>) |
| Lenovo                   | Yoga Duet 7 13IML05 82AS                         | 42       | 36       | 3       | [696A8DA807BC](<Tablet/Lenovo/Yoga/Yoga Duet 7 13IML05 82AS/696A8DA807BC>) |
| Tactus                   | GeoPad 220                                       | 42       | 42       | 1       | [AB69776A279D](<Tablet/Tactus/GeoPad/GeoPad 220/AB69776A279D>) |
| Chuwi                    | Hi10 plus tablet                                 | 42.3     | 38       | 3       | [998763CB55CC](<Tablet/Chuwi/Hi10/Hi10 plus tablet/998763CB55CC>) |
| Dell                     | Latitude 7210 2-in-1                             | 42.3     | 37       | 3       | [CD834B7AFA58](<Tablet/Dell/Latitude/Latitude 7210 2-in-1/CD834B7AFA58>) |
| Lenovo                   | MIIX 520-12IKB 20M3                              | 42.5     | 36       | 4       | [1077B69C752F](<Tablet/Lenovo/MIIX/MIIX 520-12IKB 20M3/1077B69C752F>) |
| Microtech                | etabPro4+                                        | 42.5     | 41       | 2       | [928A48291BE4](<Tablet/Microtech/etabPro4/etabPro4+/928A48291BE4>) |
| ASUSTek Computer         | T303UA                                           | 43       | 39       | 2       | [1B21032A7DA6](<Tablet/ASUSTek Computer/T303/T303UA/1B21032A7DA6>) |
| Chuwi                    | Hi8 Air                                          | 43       | 43       | 1       | [AC4301C0542A](<Tablet/Chuwi/Hi8/Hi8 Air/AC4301C0542A>) |
| Hewlett-Packard          | Elite x2 1013 G3                                 | 43       | 39       | 5       | [8986075330AF](<Tablet/Hewlett-Packard/Elite/Elite x2 1013 G3/8986075330AF>) |
| Linx                     | LAMINALTT8W4G-HBN                                | 43       | 43       | 1       | [3A8211B5B143](<Tablet/Linx/LAMINALTT8/LAMINALTT8W4G-HBN/3A8211B5B143>) |
| RuggedPC                 | RuggedPadC86V                                    | 43       | 43       | 1       | [12B444D7D8BD](<Tablet/RuggedPC/RuggedPadC86/RuggedPadC86V/12B444D7D8BD>) |
| TMAX                     | TM101W638L                                       | 43       | 43       | 1       | [BCA00D2FFDB2](<Tablet/TMAX/TM101/TM101W638L/BCA00D2FFDB2>) |
| ASUSTek Computer         | T101HA                                           | 43.5     | 37       | 31      | [47A045A8C09E](<Tablet/ASUSTek Computer/T101/T101HA/47A045A8C09E>) |
| HUAWEI                   | MateBook HZ-W19                                  | 43.5     | 38       | 2       | [FB19BBB9DBEF](<Tablet/HUAWEI/MateBook/MateBook HZ-W19/FB19BBB9DBEF>) |
| Hewlett-Packard          | Spectre x2 Detachable 12-c0XX                    | 43.5     | 35       | 2       | [949E0AA627F8](<Tablet/Hewlett-Packard/Spectre/Spectre x2 Detachable 12-c0XX/949E0AA627F8>) |

...

See all reports in the [Tablet](<Tablet>) directory.

