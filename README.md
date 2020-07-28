# Short-Temperature
Detrended fluctuation analysis, adaptive detrending and imputation data 

All codes used to separating trends from correlations and to evaluated de Hurst exponent by DFA were development in MatlabR14.
To ensure the correct performance of the algorothms, follow these steps:

1.- Unzip the mFile.zip.
2.- Use GetAdDek(n,x) to select the correct values of polynomial order k and (2n+1) window size.
3.- With the n and k values from step 2, use adda(x,n,K) to separing trends from correlations.
4.- Use GetAllF2(FileName,y,m,Nb,flag) to evaluate DFA.
5.- Use SlopeFitInt(FileName,m,flag) to generate logF2(s) vs log(s) and calculete the Hurst exponent.
