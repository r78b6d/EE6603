java c
EE6603 Assignment 1
Due Date: 5pm, Oct. 14 (Monday), 2024
Question 1
In practice, the large-scale fading model can be used to capture the power falloff. Specifically, the ratio of received power PR to transmission power PT in dB can be estimated as  K 一 Ψ, where Kis a unitlessconstant that depends on the antenna characteristics, and  Ψ  is a Gaussian distributed random variable
with mean μΨ  = 10α log10  and variance σΨ(2) . αis the path loss factor, d0 is a reference distance from
the antenna far field, and d is the communication distance between the transmitter and the receiver.
Assume that d0=1 m, d=120 m, and transmission power PT is 10 mW. Through measurement it is found
that K=-31.54 dB, α =3.7, and σΨ(⬚)=3.65 dB. What is the outage probability that the received power is
lower than then minimum requirement Pmin = -110 dBm?
Note:  dBm  (decibel-milliwatts) is  a unit  of level used to  indicate that  a power level  is  expressed in decibels (dB) with reference to one milliwatt:  10 log10  .
Question 2
A simple two-path channel model with a LOS path and a reflected path is illustrated in Fig. 1. Assume that hT = 10 m, hR = 1 m, d = 20 m. Determine the delay spread of the two-path channel.

Question 3
To combine multiple signal branches, a linear combiner is usually adopted. Specifically, the weight for each branch is  wi  = aie⬚-jθ i , where  θi    is the phase  of channel  gain  ℎi  = |ℎi |ejθ i , i=1,  … , L,  and
||a||=1 with  0 ≤ ai  ≤ 1.
There are many ways to design the linear combiner by assigning different values to a. For instance, with
MRC, the weight is proportional to the channel gain:  ai  =  .  Selection  combiner  is  also widelyadopted in communication systems. With the selection combiner, only the branch with the highest received SNR is kept, while the others are discarded. That is,  ai  = 1  for i =  argmax  |hj | and ai=0 otherwise.
Assume that the L received signals are faded independently.
1)  Prove that among all linear combiners, MRC achieves the highest received SNR.
2)  Determine whether full diversity gain can be achieved by selection combiner. State your reason.
Question 4Consider an n by m MIMO channel (i.e., 代 写EE6603 Assignment 1C/C++
代做程序编程语言with n receive antennas and m transmit antennas). Suppose that MRC is adopted at the receiver side. Determine whether full diversity gain can be achieved using the following 4 transmission schemes:
1) Transmit the information symbol s on all the antennas simultaneously;
2) Turn on one antenna at each time slot and transmit the information symbol s on the active antenna;
3) Use the Alamouti scheme when m=2;
4) Transmit x on all the antennas simultaneously, where

State your reason.
Question 5
Suppose that Nc=1024 subcarriers are used in an OFDM system with bandwidth of 1 MHz over a fading channel with delay spread of 4 μs.
1) What is the maximum achievable diversity order?
2) How to achieve the maximum diversity order?
3) How many independent symbols can be transmitted simultaneously at most each with full diversity gain? State your reason.
Question 6
Suppose that a channel has three states:
The mean transmission SNR is 0 dB. Determine:
1) the ergodic capacity without CSIT;
2) the ergodic capacity with CSIT;
3) the 0.1-outage capacity without CSIT;
4) the outage capacity with CSIT.
Question 7
Consider an SIMO system with 2 receive antennas. MRC is adopted to combine the receive signals. Let h=[h1, h2]T denote the channel gain vector. Assume no CSIT and the transmission SNR is 0 dB.
1)  Assume that h is fixed at [0.5-i, 1+i]T. Determine the channel capacity.
2)  Assume that hi=CN(0,1).
a.   Determine the ergodic channel capacity.
b.   As the number of receive antennas L increases, will the ergodic channel capacity increases linearly with L? State your reason.
Question 8
Consider an OFDM system operating over a bandwidth of 20 MHz with 1024 subcarriers. The delay spread is 1μs, the coherence time is 50 ms, and the delay constraint is 1s.
1)   Suppose that the channel gain follows Rayleigh distribution. Determine the maximum ergodic rate at SNR=0dB if full CSI is available only at the receiver side;
2)  Describe the optimal power and rate allocation (among subcarriers) strategy for maximizing the ergodic rate if the transmitter has full CSI, i.e., the channel gain of each subcarrier.

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
