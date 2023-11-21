---
title: "Blockchain web app"
collection: projects
permalink: /projects/2022-blockchain-web-app
duration: Apr 2022
---



About the project:
  - group project, worked with other four members
  - in Year 4 sem B
  - aims: make transactions between clients (ports)

Software:
  - coding: Pycharm IDE
  - API testing: Postman

<br>
<b>Blockchain example:</b>
<pre>
  chain = "[\"{\\\"index\\\": 0, \\\"transactions\\\": [], \\\"timestamp\\\": \\\"04/08/22, 12:18:20\\\", \\\"previous_hash\\\": \\\"0\\\", \\\"hash\\\": \\\"851c1a6d32faaee7456095a88e00ba285c0ed75e513431c0aaf3a961672bc766\\\", \\\"nonce\\\": 0}\", \"{\\\"index\\\": 1, \\\"transactions\\\": [\\\"{\\\\\\\"sender\\\\\\\": \\\\\\\"Interest\\\\\\\", \\\\\\\"recipient\\\\\\\": \\\\\\\"30819f300d06092a864886f70d010101050003818d0030818902818100aad3d322d97483c4d396d392101853097f28a6994da0a10d39a4160f3992b75273c0e96a06216c36c488bb1a845d7f2eabd0ccfad1279e608ba0fee44e92c7cf73d1d4c0c7701e391b86697b5ba6d1d8b9b4cd497f8d4c3bd1434e9ef9cc330bd1f7c7def6f926680900ac9122d1be6cff68b4f3bbad9f8627e84c7fc223c22b0203010001\\\\\\\", \\\\\\\"value\\\\\\\": \\\\\\\"150.0\\\\\\\"}\\\"], \\\"timestamp\\\": \\\"04/08/22, 12:18:29\\\", \\\"previous_hash\\\": \\\"851c1a6d32faaee7456095a88e00ba285c0ed75e513431c0aaf3a961672bc766\\\", \\\"hash\\\": \\\"00be3a7b6093550d7fa053b2b27c2f83835b1e434b7d8ce3834f29be35abdf31\\\", \\\"nonce\\\": 664}\", 
  \"{\\\"index\\\": 2, \\\"transactions\\\": [\\\"{\\\\\\\"sender\\\\\\\": \\\\\\\"Block_Reward\\\\\\\", \\\\\\\"recipient\\\\\\\": \\\\\\\"30819f300d06092a864886f70d010101050003818d0030818902818100c6b21b8e05d0caa6b9c67b1b8850090b04faab5da6022d0685f177ae693ef6a3a498f8d45c46c3d36929244b20960125b49f439576d4f82b171e6e68ac5082fbe9cef5ac9d3e0b832e8979eb796df1efd9e5cc26df5de8e748755fac21dd32d2b633e8bc28afb9afbc7bd51a508aec9322c2088258dbdd6b3c3c8cfa540b09e10203010001\\\\\\\", \\\\\\\"value\\\\\\\": \\\\\\\"5.0\\\\\\\"}\\\"], \\\"timestamp\\\": \\\"04/08/22, 12:18:30\\\", \\\"previous_hash\\\": \\\"00be3a7b6093550d7fa053b2b27c2f83835b1e434b7d8ce3834f29be35abdf31\\\", \\\"hash\\\": \\\"00ce940b7fcb244c753552df28a18e3d9b6df333dff429571f20eaad8808eb11\\\", \\\"nonce\\\": 747}\", 
  \"{\\\"index\\\": 3, \\\"transactions\\\": [\\\"{\\\\\\\"sender\\\\\\\": \\\\\\\"Block_Reward\\\\\\\", \\\\\\\"recipient\\\\\\\": \\\\\\\"30819f300d06092a864886f70d010101050003818d0030818902818100c6b21b8e05d0caa6b9c67b1b8850090b04faab5da6022d0685f177ae693ef6a3a498f8d45c46c3d36929244b20960125b49f439576d4f82b171e6e68ac5082fbe9cef5ac9d3e0b832e8979eb796df1efd9e5cc26df5de8e748755fac21dd32d2b633e8bc28afb9afbc7bd51a508aec9322c2088258dbdd6b3c3c8cfa540b09e10203010001\\\\\\\", \\\\\\\"value\\\\\\\": \\\\\\\"5.0\\\\\\\"}\\\"], \\\"timestamp\\\": \\\"04/08/22, 12:18:31\\\", \\\"previous_hash\\\": \\\"00ce940b7fcb244c753552df28a18e3d9b6df333dff429571f20eaad8808eb11\\\", \\\"hash\\\": \\\"0099f17010edfafa299e9df6e736491f68d991916421a999f8bde141e00053bc\\\", \\\"nonce\\\": 274}\", 
  \"{\\\"index\\\": 4, \\\"transactions\\\": [\\\"{\\\\\\\"sender\\\\\\\": \\\\\\\"Block_Reward\\\\\\\", \\\\\\\"recipient\\\\\\\": \\\\\\\"30819f300d06092a864886f70d010101050003818d0030818902818100c6b21b8e05d0caa6b9c67b1b8850090b04faab5da6022d0685f177ae693ef6a3a498f8d45c46c3d36929244b20960125b49f439576d4f82b171e6e68ac5082fbe9cef5ac9d3e0b832e8979eb796df1efd9e5cc26df5de8e748755fac21dd32d2b633e8bc28afb9afbc7bd51a508aec9322c2088258dbdd6b3c3c8cfa540b09e10203010001\\\\\\\", \\\\\\\"value\\\\\\\": \\\\\\\"5.0\\\\\\\"}\\\"], \\\"timestamp\\\": \\\"04/08/22, 12:18:31\\\", \\\"previous_hash\\\": \\\"0099f17010edfafa299e9df6e736491f68d991916421a999f8bde141e00053bc\\\", \\\"hash\\\": \\\"007ee22727e6c424f1b8a7c1290c5be1e87e1f57eff5b27e86804cd121d7b664\\\", \\\"nonce\\\": 15}\", 
  \"{\\\"index\\\": 5, \\\"transactions\\\": [\\\"{\\\\\\\"sender\\\\\\\": \\\\\\\"Block_Reward\\\\\\\", \\\\\\\"recipient\\\\\\\": \\\\\\\"30819f300d06092a864886f70d010101050003818d0030818902818100c6b21b8e05d0caa6b9c67b1b8850090b04faab5da6022d0685f177ae693ef6a3a498f8d45c46c3d36929244b20960125b49f439576d4f82b171e6e68ac5082fbe9cef5ac9d3e0b832e8979eb796df1efd9e5cc26df5de8e748755fac21dd32d2b633e8bc28afb9afbc7bd51a508aec9322c2088258dbdd6b3c3c8cfa540b09e10203010001\\\\\\\", \\\\\\\"value\\\\\\\": \\\\\\\"5.0\\\\\\\"}\\\"], \\\"timestamp\\\": \\\"04/08/22, 12:18:32\\\", \\\"previous_hash\\\": \\\"007ee22727e6c424f1b8a7c1290c5be1e87e1f57eff5b27e86804cd121d7b664\\\", \\\"hash\\\": \\\"00be269f131db52163d53904e2c9c3747ddc42a7a96620f6e6a3508fa4b79b16\\\", \\\"nonce\\\": 403}\", 
  \"{\\\"index\\\": 6, \\\"transactions\\\": [\\\"{\\\\\\\"sender\\\\\\\": \\\\\\\"Block_Reward\\\\\\\", \\\\\\\"recipient\\\\\\\": \\\\\\\"30819f300d06092a864886f70d010101050003818d0030818902818100c6b21b8e05d0caa6b9c67b1b8850090b04faab5da6022d0685f177ae693ef6a3a498f8d45c46c3d36929244b20960125b49f439576d4f82b171e6e68ac5082fbe9cef5ac9d3e0b832e8979eb796df1efd9e5cc26df5de8e748755fac21dd32d2b633e8bc28afb9afbc7bd51a508aec9322c2088258dbdd6b3c3c8cfa540b09e10203010001\\\\\\\", \\\\\\\"value\\\\\\\": \\\\\\\"5.0\\\\\\\"}\\\"], \\\"timestamp\\\": \\\"04/08/22, 12:18:32\\\", \\\"previous_hash\\\": \\\"00be269f131db52163d53904e2c9c3747ddc42a7a96620f6e6a3508fa4b79b16\\\", \\\"hash\\\": \\\"0015a68c6f1ec039a8ee677247d69c814a3790cad7695b167632b43e6ecdc995\\\", \\\"nonce\\\": 52}\"]"
</pre>