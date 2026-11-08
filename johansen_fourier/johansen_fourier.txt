# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Johansen-Fourier cointegration test Use johansen_fourier (fjohansen) With (In) R Software
install.packages("fjohansen")
library("fjohansen")
# Estimate Johansen-Fourier cointegration test Use johansen_fourier (fjohansen) With (In) R Software
johansen_fourier = read.csv("https://raw.githubusercontent.com/timbulwidodostp/johansen_fourier/main/johansen_fourier/johansen_fourier.csv",sep = ";")
johansen_fourier <- johansen_fourier(johansen_fourier, k = 1, n = 1, model = "CNR")
summary(johansen_fourier)
# Johansen-Fourier cointegration test Use johansen_fourier (fjohansen) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished