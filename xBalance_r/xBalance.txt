# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Standardized Differences for Stratified Comparisons Use xBalance (RItools) With (In) R Software
install.packages("RItools")
library("RItools")
# Estimate Standardized Differences for Stratified Comparisons Use xBalance (RItools) With (In) R Software
xBalance_data = read.csv("https://raw.githubusercontent.com/timbulwidodostp/xBalance_r/main/xBalance_r/xBalance.csv",sep = ";")
xBalance <- xBalance(xbalance ~ xbalance_1 + xbalance_2 + xbalance_3 + xbalance_4, data = xBalance_data, report = c("all"))
xBalance
# Standardized Differences for Stratified Comparisons Use xBalance (RItools) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished