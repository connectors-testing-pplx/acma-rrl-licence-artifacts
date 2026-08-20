# ACMA RRL licence-presence row artifacts

This repository publishes entity-specific row artifacts extracted from the official
**Australian Communications and Media Authority (ACMA) Register of Radiocommunications Licences
(RRL)** public bulk data download.

- Official ACMA source URL: https://web.acma.gov.au/rrl-updates/spectra_rrl.zip (redirects to https://cdn.acma.gov.au/rrl/spectra_rrl.zip)
- ACMA download description page: https://www.acma.gov.au/radiocomms-licence-data
- Data vintage (HTTP Last-Modified of spectra_rrl.zip): Wed, 19 Aug 2026 23:33:09 GMT
- Retrieved: 19 August 2026 (America/Los_Angeles)
- Locators used in every artifact: `client.csv` row keyed by CLIENT_NO and `licence.csv` row keyed by LICENCE_NO (both files are inside spectra_rrl.zip)
- CLIENT_TYPE_ID reference (client_type.csv): 1 Commonwealth Department, 2 Other Commonwealth Agency, 3 State Government, 4 Local Government, 5 Company, 6 Community or Volunteer Group, 7 Person. Only non-7 organisational clients with an ABN are included here.

Each artifact page visibly carries: the official ACMA source URL, the data vintage, the client.csv
locator, the licence.csv locator, the CLIENT_TYPE_ID organisational classification, the organisation
name and ABN, the licence number, the licence type/category, and the licence status for one claimed
service bucket.

## Index of artifacts

| service bucket | organisation | ABN | licence no | licence type | licence category | status | artifact |
|---|---|---|---|---|---|---|---|
| fixed_public_network | NBN CO LIMITED | 86136533741 | 10002272/5 | Fixed | Point to Point | Granted | [artifact](fixed_public_network/8129031__10002272-5.md) |
| fixed_public_network | TELSTRA LIMITED | 64086174781 | 10000228/1 | Fixed | Point to Point | Granted | [artifact](fixed_public_network/20053835__10000228-1.md) |
| fixed_public_network | Optus Mobile Pty Limited | 65054365696 | 10001008/1 | Fixed | Point to Point | Granted | [artifact](fixed_public_network/20017363__10001008-1.md) |
| fixed_public_network | Vodafone Australia Pty Limited | 86056161043 | 10000912/1 | Fixed | Point to Point | Granted | [artifact](fixed_public_network/536353__10000912-1.md) |
| fixed_public_network | GoldNet Pty Ltd | 42127052493 | 10058509/1 | Fixed | Point to Point | Granted | [artifact](fixed_public_network/1317869__10058509-1.md) |
| fixed_public_network | Vertical Telecoms Pty Limited | 90086050946 | 10058831/1 | Fixed | Point to Point | Granted | [artifact](fixed_public_network/1209404__10058831-1.md) |
| fixed_public_network | BIGAIR GROUP LIMITED | 57098572626 | 10100421/1 | Fixed | Point to Point (Self Coordinated) | Granted | [artifact](fixed_public_network/1141538__10100421-1.md) |
| fixed_public_network | SWOOP TELECOMMUNICATIONS PTY LTD | 87109931731 | 10097818/1 | Fixed | Point to Point | Granted | [artifact](fixed_public_network/1316295__10097818-1.md) |
| fixed_public_network | JETTECH NETWORKS PTY LTD | 90604027241 | 10059879/1 | Fixed | Point to Point | Granted | [artifact](fixed_public_network/20021546__10059879-1.md) |
| fixed_public_network | CRISP WIRELESS PTY LTD | 46615297491 | 10427457/1 | Fixed | Point to Point | Granted | [artifact](fixed_public_network/20036191__10427457-1.md) |
| fixed_public_network | WAVE1 PTY LTD | 74006395026 | 11187592/1 | Fixed | Point to Point (Self Coordinated) | Granted | [artifact](fixed_public_network/1142267__11187592-1.md) |
| fixed_public_network | March IT Pty Ltd | 12156285728 | 10239707/4 | Fixed | Point to Point | Granted | [artifact](fixed_public_network/20014348__10239707-4.md) |
| fixed_public_network | BINARY NETWORKS PTY LTD | 27132135543 | 10067422/4 | Fixed | Point to Point | Granted | [artifact](fixed_public_network/20064207__10067422-4.md) |
| fixed_public_network | Ergon Energy Telecommunications Pty Ltd | 34106459465 | 10077421/1 | Fixed | Point to Point | Granted | [artifact](fixed_public_network/1314973__10077421-1.md) |
| spectrum_public_network | TELSTRA LIMITED | 64086174781 | 10388332 | Spectrum | 2.3 GHz Band | Granted | [artifact](spectrum_public_network/20053843__10388332.md) |
| spectrum_public_network | Optus Mobile Pty Limited | 65054365696 | 10143562 | Spectrum | 2 GHz Band | Granted | [artifact](spectrum_public_network/1103276__10143562.md) |
| spectrum_public_network | Vodafone Hutchison Australia Pty Limited | 76096304620 | 10143110 | Spectrum | 2 GHz Band | Granted | [artifact](spectrum_public_network/1136980__10143110.md) |
| spectrum_public_network | NBN CO LIMITED | 86136533741 | 10424514 | Spectrum | 2.3 GHz Band | Granted | [artifact](spectrum_public_network/8129031__10424514.md) |
| spectrum_public_network | MOBILE JV PTY LIMITED | 60628500916 | 10917464 | Spectrum | 3.4 GHz Band | Granted | [artifact](spectrum_public_network/20037707__10917464.md) |
| spectrum_public_network | TPG INTERNET PTY LTD | 15068383737 | 10232073 | Spectrum | 1800 MHz Band | Granted | [artifact](spectrum_public_network/20009217__10232073.md) |
| spectrum_public_network | STARLINK AUSTRALIA PTY LTD | 68636841533 | 11190450 | Spectrum | AWL - FSS Only | Granted | [artifact](spectrum_public_network/20044061__11190450.md) |
| spectrum_public_network | AMAZON KUIPER AUSTRALIA PTY LTD | 22652115421 | 12169627 | Spectrum | AWL - FSS Only | Granted | [artifact](spectrum_public_network/20052175__12169627.md) |
| spectrum_public_network | Vocus Pty Ltd | 78127842853 | 11196513 | Spectrum | AWL - FSS Only | Granted | [artifact](spectrum_public_network/8130847__11196513.md) |
| spectrum_public_network | VIASAT AUSTRALIA PTY LIMITED | 94092010421 | 11204111 | Spectrum | AWL - FSS Only | Granted | [artifact](spectrum_public_network/20002360__11204111.md) |
| spectrum_public_network | O3B TELEPORT SERVICES (AUSTRALIA) PTY LTD | 17161700509 | 11187237 | Spectrum | AWL - FSS Only | Granted | [artifact](spectrum_public_network/20010853__11187237.md) |
| spectrum_public_network | Pivotel Group Pty Limited | 85102274322 | 12250875 | Spectrum | AWL - Standard | Granted | [artifact](spectrum_public_network/1217836__12250875.md) |
| spectrum_public_network | WORLDVU AUSTRALIA PTY LTD | 24628318963 | 11196476 | Spectrum | AWL - FSS Only | Granted | [artifact](spectrum_public_network/20041867__11196476.md) |
| spectrum_public_network | BAI TELECOMMUNICATIONS PTY LTD | 37644667694 | 12722547 | Spectrum | AWL - Standard | Granted | [artifact](spectrum_public_network/20060364__12722547.md) |
| broadcasting | AUSTRALIAN BROADCASTING CORPORATION | 52429278345 | 10099945/2 | Broadcasting | National Broadcasting | Granted | [artifact](broadcasting/1103909__10099945-2.md) |
| broadcasting | SPECIAL BROADCASTING SERVICE CORPORATION | 91314398574 | 10099947/1 | Broadcasting | National Broadcasting | Granted | [artifact](broadcasting/1133847__10099947-1.md) |
| broadcasting | Network Ten (Melbourne) Pty Limited | 39008664953 | 10062189/2 | Broadcasting | Commercial Television | Granted | [artifact](broadcasting/1143327__10062189-2.md) |
| broadcasting | Channel Seven Queensland Pty. Limited | 30009707313 | 10079618/1 | Broadcasting | Commercial Television | Granted | [artifact](broadcasting/88495__10079618-1.md) |
| broadcasting | WIN Television Qld Pty Ltd | 95009697198 | 10079626/1 | Broadcasting | Commercial Television | Granted | [artifact](broadcasting/1155726__10079626-1.md) |
| broadcasting | Prime Television (Victoria) Pty Limited | 32000390232 | 1159051/1 | Broadcasting | Commercial Television | Granted | [artifact](broadcasting/1155714__1159051-1.md) |
| broadcasting | Imparja Television Pty Ltd | 78009630120 | 1951333/1 | Broadcasting | Commercial Television | Granted | [artifact](broadcasting/233658__1951333-1.md) |
| broadcasting | Southern Cross Television (Tnt9) Pty. Limited | 63009483587 | 10109120/1 | Broadcasting | Commercial Television | Granted | [artifact](broadcasting/219214__10109120-1.md) |
| broadcasting | 2KY Broadcasters Pty Ltd | 54000820057 | 10236764/1 | Broadcasting | Commercial Radio | Granted | [artifact](broadcasting/44791__10236764-1.md) |
| broadcasting | Ace Radio Broadcasters Pty Limited | 16064882042 | 10131445/1 | Broadcasting | Commercial Radio | Granted | [artifact](broadcasting/1155536__10131445-1.md) |
| broadcasting | Rebel FM Stereo Pty Ltd | 19010874969 | 10407805/1 | Broadcasting | Commercial Radio | Granted | [artifact](broadcasting/1170617__10407805-1.md) |
| broadcasting | United Christian Broadcasters Australia Limited | 15051984402 | 10051235/3 | Broadcasting | Narrowcasting Service (LPON) | Granted | [artifact](broadcasting/1102518__10051235-3.md) |
| broadcasting | SPORTS ENTERTAINMENT NETWORK PTY LTD | 63129637378 | 10100222/2 | Broadcasting | Narrowcasting Service (LPON) | Granted | [artifact](broadcasting/8126387__10100222-2.md) |
| broadcasting | CENTRAL AUSTRALIAN ABORIGINAL MEDIA ASSOC (ABORIGINAL CORPORATION) | 32603325704 | 10967890/1 | Broadcasting | Community Broadcasting | Granted | [artifact](broadcasting/1155985__10967890-1.md) |
| aeronautical_services | Airservices Australia | 59698720886 | 10076424/1 | Aeronautical | Aeronautical Assigned System | Granted | [artifact](aeronautical_services/401054__10076424-1.md) |
| aeronautical_services | QANTAS AIRWAYS LIMITED | 16009661901 | 10272208/1 | Aeronautical | Aeronautical Assigned System | Granted | [artifact](aeronautical_services/476492__10272208-1.md) |
| aeronautical_services | VIRGIN AUSTRALIA AIRLINES PTY LTD | 36090670965 | 10461704/1 | Aeronautical | Aeronautical Assigned System | Granted | [artifact](aeronautical_services/1412657__10461704-1.md) |
| aeronautical_services | Regional Express Holdings Pty Ltd | 18099547270 | 10439346/1 | Aeronautical | Aeronautical Assigned System | Granted | [artifact](aeronautical_services/1313682__10439346-1.md) |
| aeronautical_services | Jetstar Airways Pty Ltd | 33069720243 | 11675191/1 | Aeronautical | Aeronautical Assigned System | Granted | [artifact](aeronautical_services/46945__11675191-1.md) |
| aeronautical_services | Alliance Airlines Pty Limited | 81107165980 | 10261761/1 | Aeronautical | Aeronautical Assigned System | Granted | [artifact](aeronautical_services/1142881__10261761-1.md) |
| aeronautical_services | VIRGIN AUSTRALIA REGIONAL AIRLINES PTY LTD | 76008997662 | 11559926/1 | Aeronautical | Aeronautical Assigned System | Granted | [artifact](aeronautical_services/205799__11559926-1.md) |
| aeronautical_services | NATIONAL JET EXPRESS PTY LTD | 46063561482 | 12715761/1 | Aeronautical | Aeronautical Assigned System | Granted | [artifact](aeronautical_services/20049998__12715761-1.md) |
| aeronautical_services | Skippers Aviation Pty Ltd | 76008748981 | 10728184/1 | Aeronautical | Aeronautical Assigned System | Granted | [artifact](aeronautical_services/430835__10728184-1.md) |
| aeronautical_services | SITA Technologies Australia Pty Limited | 11131818847 | 10054899/2 | Aeronautical | Aeronautical Assigned System | Granted | [artifact](aeronautical_services/20045522__10054899-2.md) |
| aeronautical_services | SWISSPORT PTY LTD | 85151147303 | 10304132/1 | Aeronautical | Aeronautical Assigned System | Granted | [artifact](aeronautical_services/20003775__10304132-1.md) |
| aeronautical_services | Dnata Airport Services Pty Limited | 30098319790 | 1426154/1 | Aeronautical | Aeronautical Assigned System | Granted | [artifact](aeronautical_services/1421512__1426154-1.md) |
| aeronautical_services | SHARP AVIATION PTY. LTD. | 68007405058 | 10902117/1 | Aeronautical | Aeronautical Assigned System | Granted | [artifact](aeronautical_services/20042234__10902117-1.md) |
| aeronautical_services | PHI INTERNATIONAL AUSTRALIA PTY LTD | 26008932189 | 10204935/1 | Aeronautical | Aeronautical Assigned System | Granted | [artifact](aeronautical_services/20031885__10204935-1.md) |
| maritime_coast | AUSTRALIAN MARITIME SAFETY AUTHORITY | 65377938320 | 10001230/1 | Maritime Coast | Limited Coast Assigned System | Granted | [artifact](maritime_coast/20000768__10001230-1.md) |
| maritime_coast | Volunteer Marine Rescue NSW | 98138078092 | 10160325/1 | Maritime Coast | Limited Coast Assigned System | Granted | [artifact](maritime_coast/1147602__10160325-1.md) |
| maritime_coast | TASMANIAN PORTS CORPORATION PTY. LTD. | 82114161938 | 10889557/1 | Maritime Coast | Limited Coast Non Assigned | Granted | [artifact](maritime_coast/1147558__10889557-1.md) |
| maritime_coast | South Australia Police | 93799021552 | 1501364/1 | Maritime Coast | Limited Coast Non Assigned | Granted | [artifact](maritime_coast/182895__1501364-1.md) |
| maritime_coast | Surf Lifesaving Queensland Inc | 27360485381 | 1443783/1 | Maritime Coast | Limited Coast Non Assigned | Granted | [artifact](maritime_coast/83314__1443783-1.md) |
| maritime_coast | Department of Fire and Emergency Services of WA | 39563851304 | 1565892/1 | Maritime Coast | Limited Coast Non Assigned | Granted | [artifact](maritime_coast/206335__1565892-1.md) |
| maritime_coast | NEWCASTLE PORT CORPORATION | 50825884846 | 1220133/1 | Maritime Coast | Limited Coast Non Assigned | Granted | [artifact](maritime_coast/20015744__1220133-1.md) |
| maritime_coast | PORTS VICTORIA | 51347220146 | 11898615/1 | Maritime Coast | Limited Coast Assigned System | Granted | [artifact](maritime_coast/20047680__11898615-1.md) |
| maritime_coast | Flinders Ports Pty Ltd | 83097377172 | 12838201/1 | Maritime Coast | Limited Coast Assigned System | Granted | [artifact](maritime_coast/1312336__12838201-1.md) |
| maritime_coast | LIFE SAVING VICTORIA LIMITED | 21102927364 | 1912125/1 | Maritime Coast | Limited Coast Marine Rescue | Granted | [artifact](maritime_coast/239612__1912125-1.md) |
| maritime_coast | KORDIA PTY LIMITED | 33062953940 | 10131454/1 | Maritime Coast | Limited Coast Assigned System | Granted | [artifact](maritime_coast/1607951__10131454-1.md) |
| maritime_coast | South Australian State Emergency Service | 39806991234 | 10996562/1 | Maritime Coast | Limited Coast Non Assigned | Granted | [artifact](maritime_coast/182734__10996562-1.md) |
| maritime_coast | The South Australian Sea Rescue Squadron Inc | 17808419845 | 10729898/1 | Maritime Coast | Limited Coast Non Assigned | Granted | [artifact](maritime_coast/1501027__10729898-1.md) |
| maritime_coast | BUREAU OF METEOROLOGY | 92637533532 | 1138054/1 | Maritime Coast | Major Coast A | Granted | [artifact](maritime_coast/435100__1138054-1.md) |
| public_safety_land_mobile | Country Fire Authority | 39255319010 | 10061249/1 | Land Mobile | Land Mobile System - > 30MHz | Granted | [artifact](public_safety_land_mobile/210019__10061249-1.md) |
| public_safety_land_mobile | DEPARTMENT OF JUSTICE AND COMMUNITY SAFETY | 32790228959 | 10265903/1 | Land Mobile | Land Mobile System - > 30MHz | Granted | [artifact](public_safety_land_mobile/20011154__10265903-1.md) |
| public_safety_land_mobile | SOUTH AUSTRALIAN GOVERNMENT RADIO NETWORK | 39370702570 | 10053539/1 | Land Mobile | Land Mobile System - > 30MHz | Granted | [artifact](public_safety_land_mobile/1507321__10053539-1.md) |
| public_safety_land_mobile | NEW SOUTH WALES GOVERNMENT TELECOMMUNICATIONS AUTHORITY | 85430594829 | 10432289/193 | Land Mobile | Land Mobile System - > 30MHz | Granted | [artifact](public_safety_land_mobile/20036348__10432289-193.md) |
| public_safety_land_mobile | WESTERN AUSTRALIA POLICE | 91724684688 | 10069961/1 | Land Mobile | Land Mobile System - > 30MHz | Granted | [artifact](public_safety_land_mobile/203860__10069961-1.md) |
| public_safety_land_mobile | DEPARTMENT OF POLICE FIRE & EMERGENCY MANAGEMENT (TAS) | 19173586474 | 11220953/1 | Land Mobile | Land Mobile System - > 30MHz | Granted | [artifact](public_safety_land_mobile/20046753__11220953-1.md) |
| public_safety_land_mobile | NSW Police Force | 43408613180 | 10000201/1 | Land Mobile | Land Mobile System - > 30MHz | Granted | [artifact](public_safety_land_mobile/31823__10000201-1.md) |
| public_safety_land_mobile | QUEENSLAND POLICE SERVICE | 29409225509 | 10055685/1 | Land Mobile | Land Mobile System 0-30MHz | Granted | [artifact](public_safety_land_mobile/20060946__10055685-1.md) |
| public_safety_land_mobile | NSW RURAL FIRE SERVICE | 25003129221 | 10068530/1 | Land Mobile | Paging System - Exterior | Granted | [artifact](public_safety_land_mobile/5832__10068530-1.md) |
| public_safety_land_mobile | QUEENSLAND FIRE AND EMERGENCY SERVICES | 93035163778 | 10074583/1 | Land Mobile | Land Mobile System - > 30MHz | Granted | [artifact](public_safety_land_mobile/84379__10074583-1.md) |
| public_safety_land_mobile | State Emergency Service (Nsw) | 88712649015 | 10475840/1 | Land Mobile | Land Mobile System 0-30MHz | Granted | [artifact](public_safety_land_mobile/516364__10475840-1.md) |
| public_safety_land_mobile | ST JOHN AMBULANCE WESTERN AUSTRALIA LTD. | 55028468715 | 10090930/1 | Land Mobile | Land Mobile System - > 30MHz | Granted | [artifact](public_safety_land_mobile/206243__10090930-1.md) |
| public_safety_land_mobile | SOUTH AUSTRALIAN COUNTRY FIRE SERVICE | 97677077835 | 10053535/1 | Land Mobile | Land Mobile System - > 30MHz | Granted | [artifact](public_safety_land_mobile/169283__10053535-1.md) |
| public_safety_land_mobile | ST. JOHN AMBULANCE AUSTRALIA INCORPORATED | 83373110633 | 10005982/1 | Land Mobile | Land Mobile System - > 30MHz | Granted | [artifact](public_safety_land_mobile/1144303__10005982-1.md) |
