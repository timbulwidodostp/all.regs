# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Goodness of Fit Measures for a Regression Hierarchy Use all.regs (hier.part) With (In) R Software
install.packages("remotes")
remotes::install_github("cjbwalsh/hier.part")
library("hier.part")
all.regs = read.csv("https://raw.githubusercontent.com/timbulwidodostp/all.regs/main/all.regs/all.regs.csv",sep = ";")
# Estimation Goodness of Fit Measures for a Regression Hierarchy Use all.regs (hier.part) With (In) R Software
all.regs_ <- all.regs[,2:8]
all.regs <- all.regs(all.regs$lec, all.regs_, fam = "gaussian", gof = "Rsqu", print.vars = TRUE)
head(all.regs, 36)
# Goodness of Fit Measures for a Regression Hierarchy Use all.regs (hier.part) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished