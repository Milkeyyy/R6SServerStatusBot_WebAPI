# R6SSS Web API
![R6SSS API](https://cronitor.io/badges/MAB0MW/production/nU_tW7xGKHIHVxRrspK61JDTEP0.svg)

URL: https://api.r6sss.milkeyyy.com

- [**đȘ Discord Bot**](https://github.com/Milkeyyy/R6SServerStatusBot)
- [**đ ăă­ă„ăĄăłă** (é©ćœ)](https://api.r6sss.milkeyyy.com/docs)

### äŸ
- `GET` - `https://api.r6sss.milkeyyy.com`
```json
{"PC":{"Status":{"Connectivity":"Operational","Authentication":"Operational","Leaderboard":"Operational","Matchmaking":"Operational","Purchase":"Operational"},"Maintenance":false},"Stadia":{"Status":{"Connectivity":"Operational","Authentication":"Operational","Leaderboard":"Operational","Matchmaking":"Operational","Purchase":"Operational"},"Maintenance":false},"PS4":{"Status":{"Connectivity":"Operational","Authentication":"Operational","Leaderboard":"Operational","Matchmaking":"Operational","Purchase":"Operational"},"Maintenance":false},"PS5":{"Status":{"Connectivity":"Operational","Authentication":"Operational","Leaderboard":"Operational","Matchmaking":"Operational","Purchase":"Operational"},"Maintenance":false},"XBOXONE":{"Status":{"Connectivity":"Operational","Authentication":"Operational","Leaderboard":"Operational","Matchmaking":"Operational","Purchase":"Operational"},"Maintenance":false},"XBOX SERIES X":{"Status":{"Connectivity":"Operational","Authentication":"Operational","Leaderboard":"Operational","Matchmaking":"Operational","Purchase":"Operational"},"Maintenance":false}}
```

- `GET` - `https://api.r6sss.milkeyyy.com?platform=PS4&platform=PS5`
```json
{"PS4":{"Status":{"Connectivity":"Operational","Authentication":"Operational","Leaderboard":"Operational","Matchmaking":"Operational","Purchase":"Operational"},"Maintenance":false},"PS5":{"Status":{"Connectivity":"Operational","Authentication":"Operational","Leaderboard":"Operational","Matchmaking":"Operational","Purchase":"Operational"},"Maintenance":false}}
```

#### ăă©ăĄăŒăżăŒă«æćźă§ăăăă©ăăăă©ăŒă 
ăă©ăăăă©ăŒă ăæćźăăȘăć ŽćăŻăăăčăŠăźăă©ăăăă©ăŒă ăźă”ăŒăăŒăčăăŒăżăčăććŸă§ăăŸăă
- æ­Łćžžă«æŽæ°ăăăăă©ăăăă©ăŒă 
  - `PC` (Stadia ăźæć ±ăć«ă)
  - `PS4` (PS5 ăźæć ±ăć«ă)
  - `XBOXONE` (Xbox Series X/S ăźæć ±ăć«ă)
- ä»„äžăźăă©ăăăă©ăŒă ăŻăă”ăŒăăŒăćæ­ąăăŠăăăăăĄăłăăăłăčăèĄăăăŠăăć Žćă§ăăUbisoftăźă”ăŒăăŒăăććŸă§ăăæć ±ăæŽæ°ăăăȘăăăăăčăăŒăżăčăæ­Łćžžă«æŽæ°ăăăŸăăă 
  - `Stadia`
  - `PS5`
  - `XBOX SERIES X`
