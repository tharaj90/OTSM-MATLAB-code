# OTSM-MATLAB-code
Orthogonal Time Sequency Multiplexing Modulation (OTSM) is single-carrier modulation scheme which offers superior performance as compared to the widely used OFDM modulation in high mobility channels [R1,R2]. OTSM also offers similar error performance as the recently proposed OTFS modulation scheme. The information symbols in OTSM are multiplexed in the delay-sequency domain using the Walsh Hadamard transform (WHT). Note that sequency (analogous to frequency) is the number of zero-crossings per unit interval. Since WHT does not require multiplicative operations and requires only addition and subtraction operations, the OTSM modulation/demodulation complexity is significantly low as compared to OFDM and OTFS modulation.

This code package is based on the system model and detection algorithms presented in [R1,R2]. Three detection methods are provided and, the variable names, descriptions and a sample BER plot are provided in the read-me file in the package. OTSM with zero-padding between time domain blocs is considered in this code. The users can modify the code for cyclic prefix per block or frame accordingly or try new detection methods. Please cite [R1,R2] if the users wish to use/publish research using the OTSM-matlab-code files.



[R1]. T. Thaj and E. Viterbo, "Orthogonal Time Sequency Multiplexing Modulation," 2021 IEEE Wireless Communications and Networking Conference (WCNC), 2021, pp. 1-7, doi: 10.1109/WCNC49053.2021.9417451.
[R2]. T. Thaj, E. Viterbo and Y. Hong, "Orthogonal Time Sequency Multiplexing Modulation: Analysis and Low-Complexity Receiver Design," in IEEE Transactions on Wireless Communications, doi: 10.1109/TWC.2021.3088479.



