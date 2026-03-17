	This is a split keyboard loosely based on Hack Club's (https://stasis.hackclub.com/starter-projects/split-keyboard.)
It runs from bluetooth, on two NRF52840 Pro Micro clone boards that you can get on aliexpress for cheap. 

Why'd I make it?
Its a bit of a deviation from the standard split keyboard dealy. Generally people use these same switches, but they

A. Expose the MCU on the top face of the keyboard halves
B. Use very few keys (Like a 45 percent keyboard or something along those lines)
and 
C. Use super flat, spread out keycaps.
I'm not crazy about any of these. I like traditional keyboards okay, and I have no idea how people remember which key is which on their splits. I wanted mine to be more standard- with the split for ergnomics but fairly status quo
everywhere else. I like the feeling of regular keycaps-- I like the look as well. I wanted to design my own keycaps. I got the little plug insert bits just from user fivedee on printables \
(https://www.printables.com/model/1069263-15x15-minimal-spaced-kailh-choc-keycap/files)  
Everything else I cut out and built my own. The result is some monster sized caps- turning low profile switches into a very much not low profile keyboard- which is what I wanted, but I might need to change things in the future and 
make my caps lighter. As of now they are untested. 
<img width="428" height="290" alt="Capture" src="https://github.com/user-attachments/assets/23c2f170-5ba9-48fb-bb26-d121ead9d253" />


The design is screws coming up from the bottom. The two sides mesh together with a nice offset surface.
<img width="1034" height="483" alt="FinalReal" src="https://github.com/user-attachments/assets/68fcb5e4-6128-43bf-9d11-faa1ada35b2a" />
The PCB is actually reversed for the final- because it has kailh hot swap switches on it
<img width="1241" height="512" alt="image" src="https://github.com/user-attachments/assets/ec115cf0-db95-4047-a011-083d466d5e5d" />


BOM
| Item | Count | Price Per Unit | Total Price | Link | Status |
|---|---:|---:|---:|---|---|
| M2 Heatset Inserts (3.2 x 3.2mm) | 21 | N/A | N/A | N/A | Have |
| NRF52840 Dev Board | Pack x2 | N/A | $0.99 | [Link](https://www.aliexpress.us/item/3256807018711621.html?spm=a2g0o.cart.0.0.46a538daSh2DJS&mp=1&pdp_npi=6%40dis%21USD%21USD%207.23%21USD%200.99%21%21USD%200.99%21%21%21%402101e83017737027362077455e2f9f%2112000052145987931%21ct%21US%217434485779%21%211%210%21&_gl=1*qex46*_gcl_aw*R0NMLjE3NzM3MDE3OTIuQ2p3S0NBancxTjdOQmhBb0Vpd0FjUGNocDZjZm9MbWJFeHJpeEhseGhxQm5sM19CVXFTZWdTNlA5QUllUGg1SnFUQW82TlVySkJXMzF4b0N3UUVRQXZEX0J3RQ..*_gcl_dc*R0NMLjE3NzM3MDE3OTIuQ2p3S0NBancxTjdOQmhBb0Vpd0FjUGNocDZjZm9MbWJFeHJpeEhseGhxQm5sM19CVXFTZWdTNlA5QUllUGg1SnFUQW82TlVySkJXMzF4b0N3UUVRQXZEX0J3RQ..*_gcl_au*NDE0NzgwMTk1LjE3NzMxNzg3NzI.*_ga*MjEzOTYzMzUyMTA0MjEwOC4xNzczMTc4NzcxNDEx*_ga_VED1YSGNC7*czE3NzM3MDA1MzQkbzUkZzEkdDE3NzM3MDI3MzkkajMxJGwwJGgw&gatewayAdapt=glo2usa) | Need |
| PCB | Pack x5 (dev min) | N/A | $25.70 | N/A? | Need |
| Li-ion Poly Battery 5000mAh | Pack x2 | N/A | $14.13 | [Link](https://www.aliexpress.us/item/3256809787664995.html?spm=a2g0o.cart.0.0.610438daQ8KPR9&mp=1&pdp_npi=6%40dis%21USD%21USD%2031.41%21USD%2014.13%21%21USD%2014.13%21%21%21%402101e83017737024323317715e2f9f%2112000050732619666%21ct%21US%217434485779%21%211%210%21&_gl=1*4rofoi*_gcl_aw*R0NMLjE3NzM3MDE3OTIuQ2p3S0NBancxTjdOQmhBb0Vpd0FjUGNocDZjZm9MbWJFeHJpeEhseGhxQm5sM19CVXFTZWdTNlA5QUllUGg1SnFUQW82TlVySkJXMzF4b0N3UUVRQXZEX0J3RQ..*_gcl_dc*R0NMLjE3NzM3MDE3OTIuQ2p3S0NBancxTjdOQmhBb0Vpd0FjUGNocDZjZm9MbWJFeHJpeEhseGhxQm5sM19CVXFTZWdTNlA5QUllUGg1SnFUQW82TlVySkJXMzF4b0N3UUVRQXZEX0J3RQ..*_gcl_au*NDE0NzgwMTk1LjE3NzMxNzg3NzI.*_ga*MjEzOTYzMzUyMTA0MjEwOC4xNzczMTc4NzcxNDEx*_ga_VED1YSGNC7*czE3NzM3MDA1MzQkbzUkZzEkdDE3NzM3MDI3NDUkajI1JGwwJGgw&gatewayAdapt=glo2usa) | Need |
| Choc V1 Switches | 77 | N/A | N/A | [Link](https://www.aliexpress.us/item/3256809185516557.html?src=google&pdp_npi=4%40dis%21USD%217.09%217.09%21%21%21%21%21%40%2112000048898680192%21ppc%21%21%21&src=google&albch=shopping&acnt=708-803-3821&isdl=y&slnk=&plac=&mtctp=&albbt=Google_7_shopping&aff_platform=google&aff_short_key=UneMJZVf&gclsrc=aw.ds&albagn=888888&ds_e_adid=&ds_e_matchtype=&ds_e_device=c&ds_e_network=x&ds_e_product_group_id=&ds_e_product_id=en3256809185516557&ds_e_product_merchant_id=5337023700&ds_e_product_country=US&ds_e_product_language=en&ds_e_product_channel=online&ds_e_product_store_id=&ds_url_v=2&albcp=19558607238&albag=&isSmbAutoCall=false&needSmbHouyi=false&gad_source=1&gad_campaignid=19566915268&gbraid=0AAAAAD6I-hHE-H-7J2P63qEfKvxg4aSxQ&gclid=CjwKCAjw1N7NBhAoEiwAcPchp6cfoLmbExrixHlxhqBnl3_BUqSegS6P9AIePh5JqTAo6NUrJBW31xoCwQEQAvD_BwE&gatewayAdapt=glo2usa) | Have |
| PG1350 Sockets | 77 | N/A | N/A | [Link](https://www.aliexpress.us/item/3256805079542148.html?src=google&pdp_npi=4%40dis%21USD%211.54%211.11%21%21%21%21%21%40%2112000032415288517%21ppc%21%21%21&src=google&albch=shopping&acnt=708-803-3821&isdl=y&slnk=&plac=&mtctp=&albbt=Google_7_shopping&aff_platform=google&aff_short_key=UneMJZVf&gclsrc=aw.ds&albagn=888888&ds_e_adid=&ds_e_matchtype=&ds_e_device=c&ds_e_network=x&ds_e_product_group_id=&ds_e_product_id=en3256805079542148&ds_e_product_merchant_id=109258156&ds_e_product_country=US&ds_e_product_language=en&ds_e_product_channel=online&ds_e_product_store_id=&ds_url_v=2&albcp=19558607238&albag=&isSmbAutoCall=false&needSmbHouyi=false&gad_source=1&gad_campaignid=19566915268&gbraid=0AAAAAD6I-hHE-H-7J2P63qEfKvxg4aSxQ&gclid=CjwKCAjw1N7NBhAoEiwAcPchp13K3jXwFwk-rPK55fXNXv5V-aJNthOR1-a6wdnraypLKRLxYWzpIRoCTwwQAvD_BwE&gatewayAdapt=glo2usa) | Have |
| 1N4184W Diodes | 100 | N/A | $4.77 | [Link](https://www.aliexpress.us/item/3256809772352005.html?spm=a2g0o.cart.0.0.46a538daSh2DJS&mp=1&pdp_npi=6%40dis%21USD%21USD%209.54%21USD%204.77%21%21USD%204.77%21%21%21%402101e83017737027362077455e2f9f%2112000050691298739%21ct%21US%217434485779%21%211%210%21&_gl=1*4o9f7y*_gcl_aw*R0NMLjE3NzM3MDE3OTIuQ2p3S0NBancxTjdOQmhBb0Vpd0FjUGNocDZjZm9MbWJFeHJpeEhseGhxQm5sM19CVXFTZWdTNlA5QUllUGg1SnFUQW82TlVySkJXMzF4b0N3UUVRQXZEX0J3RQ..*_gcl_dc*R0NMLjE3NzM3MDE3OTIuQ2p3S0NBancxTjdOQmhBb0Vpd0FjUGNocDZjZm9MbWJFeHJpeEhseGhxQm5sM19CVXFTZWdTNlA5QUllUGg1SnFUQW82TlVySkJXMzF4b0N3UUVRQXZEX0J3RQ..*_gcl_au*NDE0NzgwMTk1LjE3NzMxNzg3NzI.*_ga*MjEzOTYzMzUyMTA0MjEwOC4xNzczMTc4NzcxNDEx*_ga_VED1YSGNC7*czE3NzM3MDA1MzQkbzUkZzEkdDE3NzM3MDI3MzUkajM1JGwwJGgw&gatewayAdapt=glo2usa) | Need |
| 0805 820k Ohm SMD resistor | 100 | N/A | N/A | N/A | Have? |
| 0805 2M Ohm SMD resistor | 100 | N/A | N/A | N/A | Have? |
| Shipping |  |  | $20.73 |  |  |
| Coupons |  |  | -$13.00 |  |  |
| **Total** |  |  | **$53.32** |  |  |
