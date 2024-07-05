# network-simulation
給定一個 simple tree 的 topo 與其 bandwidth,  
給定傳輸封包的起始點(h1, h3), 終點(h5, h7), 所有節點間皆是有線傳輸,
h1 傳播路徑: h1→ac1→ag1→core→ag2→ac3→h5,
h3 傳播路徑: h3→ac2→ag1→core→ag2→ac4→h5,
其中 ag1->core->ag2 為 bottleneck。    
  
額外在 ag1->core->ag2 加上一個 wireless link(只有這個 link 是 wireless), 並給定其 bandwidth,  
模擬整個 topo 的 bandwidth(即接收端每秒接收的 data)。  
  
需用 ns3 或 mininet-wifi 之類的網路軟體進行模擬,  
需讓我能使用並確認正確性(topo 是否建立正確, 是否同時模擬 wired 與 wireless)
![image](https://github.com/OuO333333/network-simulation/assets/37506309/dd995244-8fff-480a-93d6-1a7472bedf71)
