# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Detecting and modeling temporal effect heterogeneity with panel data Use dynamr With (In) R Software
install.packages("remotes")
remotes::install_github("dnkent/dynamr")
install.packages("ISLR")
library("ISLR")
library("dynamr")
# Estimate Detecting and modeling temporal effect heterogeneity with panel data Use dynamr With (In) R Software
dynamr = read.csv("https://raw.githubusercontent.com/timbulwidodostp/dynamr/main/dynamr/dynamr.csv",sep = ";")
dynamr <- dynamr(dat = dynamr, time_var = "Year", formula = Today ~ Lag1 + Lag2, window_size = 1, family = "gaussian", N = 50)
dynamr
# Estimate mixed tobit regression models parameters with mixed effects Use mixedtobit With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished