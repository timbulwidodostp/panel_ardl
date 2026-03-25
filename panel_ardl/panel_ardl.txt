# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Panel Autoregressive Distributed Lag (ARDL) Estimation Use panel_ardl (ardlverse) With (In) R Software
install.packages("ardlverse")
library("ardlverse")
# Estimation Panel Autoregressive Distributed Lag (ARDL) Estimation Use panel_ardl (ardlverse) With (In) R Software
panel_ardl = read.csv("https://raw.githubusercontent.com/timbulwidodostp/panel_ardl/main/panel_ardl/panel_ardl.csv",sep = ";")
panel_ardl <- panel_ardl(gdp ~ inflation + investment, data = panel_ardl, id = "country", time = "year", estimator = "pmg")
summary(panel_ardl)
# Panel Autoregressive Distributed Lag (ARDL) Estimation Use panel_ardl (ardlverse) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished