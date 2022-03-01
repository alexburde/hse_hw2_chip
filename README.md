# hse_hw2_chip
Цель работы: научиться определять участки генома, где присутствует определенная гистоновая модификация в конкретном типе клеток с помощью анализа ChIP-Seq данных.
# Обязательная часть задания.
Для работы выбраны клеточная линия (MM.1S), гистоновая метка (H3K27ac) и файл контроля.
ID fastq файлов: ENCFF630ZFU (реплика1), ENCFF783XFU (реплика2), ENCFF630PTQ (контроль)
# Отчеты FastQC:

ENCFF630ZFU (реплика1) ДО ПОДРЕЗАНИЯ ЧТЕНИЙ
<p float="left">
<img width="141" alt="image" src="https://user-images.githubusercontent.com/93148620/156215869-f866fc9d-bbb1-404a-9518-4fa98670df52.png"/>
<img width="254" alt="image" src="https://user-images.githubusercontent.com/93148620/156215222-e400e1e8-915e-4177-b8dc-4ebeaff699be.png"/>
<img width="439" alt="image" src="https://user-images.githubusercontent.com/93148620/156215557-75f86f85-6f61-4212-ad47-d55b0d50e7f5.png"/>
<img width="450" alt="image" src="https://user-images.githubusercontent.com/93148620/156215580-16b99c1a-7329-4568-a190-1dbaa633831a.png"/>
<img width="439" alt="image" src="https://user-images.githubusercontent.com/93148620/156215669-813c0a4b-2e8f-41d1-b08c-baf2d52baf9d.png"/>
<img width="446" alt="image" src="https://user-images.githubusercontent.com/93148620/156215693-3ae7ba72-1009-4247-ac3d-3ce9ff2864de.png"/>
<img width="435" alt="image" src="https://user-images.githubusercontent.com/93148620/156215775-0eced36b-9bae-48c4-9536-0fbfbe7bac42.png"/>
<img width="449" alt="image" src="https://user-images.githubusercontent.com/93148620/156215807-3a036c43-491b-4072-a2e3-bc9e715605de.png"/>
</p>
ENCFF630ZFU (реплика1) ПОСЛЕ ПОДРЕЗАНИЯ ЧТЕНИЙ
<p float="left">
<img width="291" alt="image" src="https://user-images.githubusercontent.com/93148620/156217812-9e6add22-afbd-42b2-b1bb-d0c52c795f62.png">
<img width="161" alt="image" src="https://user-images.githubusercontent.com/93148620/156217862-7d5e98a1-69e4-4810-a899-9f08a9144f40.png">
<img width="432" alt="image" src="https://user-images.githubusercontent.com/93148620/156217932-b5a44a54-d327-47f4-8c07-105c65bc57d7.png">
<img width="439" alt="image" src="https://user-images.githubusercontent.com/93148620/156217961-605bb58a-5d2c-40f5-9925-88e867ddf32a.png">
<img width="442" alt="image" src="https://user-images.githubusercontent.com/93148620/156217999-91e224a3-192b-401c-b378-52ecb100ae11.png">
<img width="439" alt="image" src="https://user-images.githubusercontent.com/93148620/156218030-9d4b1b5e-2747-4a15-b0bb-18434523fc91.png">
<img width="438" alt="image" src="https://user-images.githubusercontent.com/93148620/156218061-2d50ef04-4fcc-4b57-b2e3-cb7ea45c7acb.png">
<img width="440" alt="image" src="https://user-images.githubusercontent.com/93148620/156218134-64d05da0-0f48-4cb8-8d74-940a86eb3cf7.png">
</p>
ENCFF783XFU (реплика2) ДО ПОДРЕЗАНИЯ ЧТЕНИЙ
<p float="left">
<img width="197" alt="image" src="https://user-images.githubusercontent.com/93148620/156218252-09fbaa2a-56d0-42b5-9a6a-dffc014de115.png">
<img width="103" alt="image" src="https://user-images.githubusercontent.com/93148620/156218277-307c89ea-d772-4420-a7e1-bbe67ebf4eea.png">
<img width="330" alt="image" src="https://user-images.githubusercontent.com/93148620/156218300-1acb7209-e819-4118-beb1-7874e886de12.png">
<img width="334" alt="image" src="https://user-images.githubusercontent.com/93148620/156218328-0e500df0-5b4a-4b62-9159-65f3114efa85.png">
<img width="330" alt="image" src="https://user-images.githubusercontent.com/93148620/156218353-860b52e9-286a-44ba-b923-22f2ef9d76a4.png">
<img width="332" alt="image" src="https://user-images.githubusercontent.com/93148620/156218400-f30417c5-06b7-4a19-b351-03dc88dceeaa.png">
<img width="328" alt="image" src="https://user-images.githubusercontent.com/93148620/156218449-890e4de6-898d-4b85-b603-b2706816e133.png">
<img width="340" alt="image" src="https://user-images.githubusercontent.com/93148620/156218516-38e1b88e-4eac-43d0-b930-f541cfd91768.png">
</p>
ENCFF783XFU (реплика2) ПОСЛЕ ПОДРЕЗАНИЯ ЧТЕНИЙ
<p float="left">
  <img width="292" alt="image" src="https://user-images.githubusercontent.com/93148620/156219039-7be4217c-abaa-47a8-85e9-0177ea4d1e56.png">
<img width="151" alt="image" src="https://user-images.githubusercontent.com/93148620/156219066-7b6d5aba-f6cf-49af-b15f-06f6f85f5042.png">
<img width="442" alt="image" src="https://user-images.githubusercontent.com/93148620/156219100-9fc0cc63-e2f6-42b0-a84c-f4ab9f27e93f.png">
<img width="432" alt="image" src="https://user-images.githubusercontent.com/93148620/156219115-a17dece7-03a9-4b34-9e42-cafd6ca7ddcf.png">
<img width="451" alt="image" src="https://user-images.githubusercontent.com/93148620/156219138-c960f13e-fbe1-423a-92b4-998a4e3e3026.png">
<img width="436" alt="image" src="https://user-images.githubusercontent.com/93148620/156219162-c59519bf-68de-4923-b234-4dbe2e509cae.png">
<img width="434" alt="image" src="https://user-images.githubusercontent.com/93148620/156219207-2057c73a-1b2e-421a-8169-0bc1ec23a2d8.png">
<img width="436" alt="image" src="https://user-images.githubusercontent.com/93148620/156219232-c4f137c9-b2fe-4d1f-b149-45e032a0faaa.png">
</p>
 ENCFF630PTQ (контроль) ДО ПОДРЕЗАНИЯ ЧТЕНИЙ
 <p float="left">
  <img width="250" alt="image" src="https://user-images.githubusercontent.com/93148620/156219397-c701ab36-b8ca-4fb8-b172-8c048156f3cc.png">
<img width="140" alt="image" src="https://user-images.githubusercontent.com/93148620/156219439-095f0ee5-66d4-4de7-8683-dba1da058ed4.png">
<img width="436" alt="image" src="https://user-images.githubusercontent.com/93148620/156219471-fdfbeb50-eefb-4873-b389-cbc316a7ade9.png">
<img width="436" alt="image" src="https://user-images.githubusercontent.com/93148620/156219493-fc2d82dc-51a4-426b-b511-d2f71b699560.png">
<img width="438" alt="image" src="https://user-images.githubusercontent.com/93148620/156219522-daf77872-e7df-4844-bd11-6ad7fe6ab0d9.png">
<img width="438" alt="image" src="https://user-images.githubusercontent.com/93148620/156219541-67cf52cc-6f25-44d4-9ecc-e811bba464de.png">
<img width="446" alt="image" src="https://user-images.githubusercontent.com/93148620/156219573-fffef0eb-46ec-44b6-9136-079c67aac174.png">
<img width="440" alt="image" src="https://user-images.githubusercontent.com/93148620/156219584-80e62041-54c7-4982-bcb2-0232b73b09fc.png">
</p>
ENCFF630PTQ (контроль) ПОСЛЕ ПОДРЕЗАНИЯ ЧТЕНИЙ
<p float="left">
  <img width="266" alt="image" src="https://user-images.githubusercontent.com/93148620/156219717-475aafbd-8596-4cfd-ad3b-b9d0e30d659c.png">
<img width="137" alt="image" src="https://user-images.githubusercontent.com/93148620/156219749-e09d9e42-d529-4278-b1bd-2d7120b3ea8d.png">
<img width="433" alt="image" src="https://user-images.githubusercontent.com/93148620/156219766-c32c2c8c-ec6d-477b-8e61-cd7933112112.png">
<img width="442" alt="image" src="https://user-images.githubusercontent.com/93148620/156219792-2cd514ba-4617-4c9f-9550-b86b05d19c09.png">
<img width="433" alt="image" src="https://user-images.githubusercontent.com/93148620/156219813-08dd4ced-977b-402c-83ef-e1f4055f29be.png">
<img width="437" alt="image" src="https://user-images.githubusercontent.com/93148620/156219830-c96613fc-6e86-4907-8f9c-fcdc23071d59.png">
<img width="435" alt="image" src="https://user-images.githubusercontent.com/93148620/156219858-0c125bcc-5319-438d-938a-d87e2ea113d8.png">
<img width="436" alt="image" src="https://user-images.githubusercontent.com/93148620/156219880-263469bc-cb89-4dcf-b989-ccc1cc02e7f1.png">
</p>
# Таблица со статистикой
|ChIP-seq                |ENCFF630ZFU       |ENCFF783XFU       |ENCFF630PTQ (контроль)|
|:-----------------------|:----------------:|:----------------:|:--------------------:|
|TOTAL READS             | 29121883         | 72466541         |     21721691         |
|aligned exactly 1 time  | 865020 (2.97%)   | 2081885 (2.87%)  | 687330 (3.16%)       |
|aligned >1 times        | 2685448 (9.22%)  | 7321165 (10.10%) | 2544401 (11.71%)     |
|aligned 0 times         | 25571415 (87.81%)| 63063491 (87.02%)| 818489960 (85.12%)   |

# Venn diagram
<img width="523" alt="image" src="https://user-images.githubusercontent.com/93148620/156232118-07a3542a-b8c9-4020-a1c5-1d00412e618a.png">
<img width="510" alt="image" src="https://user-images.githubusercontent.com/93148620/156232085-15dd915d-8827-414e-9ef5-2009628caf31.png">
<img width="513" alt="image" src="https://user-images.githubusercontent.com/93148620/156232168-3273b90c-d65d-49bb-ba37-b70151a87f5a.png">
<img width="479" alt="image" src="https://user-images.githubusercontent.com/93148620/156232236-2a002cc9-761e-4e63-89b7-3579685c8019.png">



