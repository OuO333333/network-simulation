# network-simulation
給定一個 simple tree 的 topo 與其 bandwidth,  
給定傳輸封包的起始點, 所有節點間皆是有線傳輸,  
其中 ag1->core->ag2 為 bottleneck,  
模擬整個 topo 的 bandwidth。    
  
在 ag1->core->ag2 加上一個 wireless link, 並給定其 bandwidth,  
模擬整個 topo 的 bandwidth。  
  
需用 ns3, mininet-wifi 等等軟體進行模擬,  
需讓我能使用並確認正確性(topo 是否建立正確, 是否同時模擬 wired 與 wireless)
