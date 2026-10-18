# Mono-carrier Acoustic Communication Technology Research [with MATLAB Code]

Abstract Underwater wireless communication is used in marine research and Defense It has been widely concerned for its key role in rescue and resource development. As an effective carrier of information transmission in water, Promoted the development of hydroacoustic communication technology. Among them, single-carrier modulation technology is due to its high spectrum utilization rate. The structure is simple and easy to implement, etc. It is widely used in underwater acoustic communication systems. Underwater acoustic communication technology has gone through analog modulation, Digital modulation until advanced modulation stage, Developed including AM, FM,  PSK,  QAM and other modulation methods, Each method has its advantages and disadvantages, as well as its applicable scenarios. For the complexness of underwater acoustic channels. Time-varying Significant issues such as multipath effects. Channel equalization technology is introduced to improve communication quality.Especially the frequency domain equalization technology. Because of its lower computational complexity. Strong anti-multipath interference capability. It can achieve jointly decoded code and occupy an important position in single-carrier underwater acoustic communication. The research of single carrier acoustic communication has been deepening since 1970s. From non-coherent modulation to coherent modulation. Then the receiver structure improvement based on judgment feedback balance and digital phase-locked loop technology is introduced. Continuously optimize the channel estimation and signal recovery processes. Current research hotspots include frequency-division multiplexing and Advanced schemes such as time-reversal processing and jointly decoded coding. Aims to improve communication speed. Enhances interference resistance and expands coverage range.Single-carrier acoustic communication technology has the advantages of simple implementation and The advantage of lower costs. However, it also faces the weak interference resistance. Low frequency band utilization Challenges such as communication rate limitations. Furthermore, The report focuses on discussing the effects of multipath. The effect of intersymbol interference on the performance of hydroacoustic communication. The basic principles and different methods of two kinds of channel equalization techniques, i.e. Time domain equalization and frequency domain equalization, are introduced. Emphasizes the importance of balanced technology in reducing signal distortion. The importance of enhancing communication reliability and reducing error rates.
Introduction 1.1 Research Background and Significance
Underwater wireless communication refers to the technology of transmitting and receiving information in water. It is for the development of the ocean. Ocean science research, Ocean defense It plays an important role and value in areas such as marine rescue. Due to the very large attenuation of electromagnetic waves in water, Sound waves become the main information carrier of underwater wireless communication. Therefore, hydroacoustic communication is the mainstream technology of underwater wireless communication.
The development of underwater acoustic communication has gone through from analog modulation to digital modulation. From non-coherent modulation to coherent modulation. The process from single-carrier modulation to multi-carrier modulation. Among them, Single-carrier modulation is a technique that modulates information onto a carrier. It has high spectral utilization. Simple structure. Easy to implement, etc. Therefore, it has been widely used in underwater acoustic communication.
However, The complexity of the underwater acoustic channel. Time-varying Multipath effect Inter-symbol interference Noise interference, etc. These factors will cause distortion and attenuation of hydroacoustic signals. Reduce the performance and reliability of underwater acoustic communication. To solve these problems, Channel equalization technology is introduced into underwater acoustic communication. It is a method that uses channel estimation and signal processing. To counteract the adverse effects of the channel on the signal. Techniques for restoring original signals. Channel equalization technology can be divided into time domain equalization and frequency domain equalization. Among them, Frequency domain equalization is a technique that converts signals into the frequency domain for equalization processing. It has low computational complexity. Strong anti-multipath interference capability. Easy to realize the advantages of jointly balanced decoding. Therefore, it has received widespread attention and research in single-carrier acoustic communication.
The development of hydroacoustic communication technology can be divided into three stages: the analog modulation stage, the digital modulation stage, and the advanced modulation stage.
The simulation modulation stage is from the early 20th century to the mid-20th century. This stage mainly uses analog modulation techniques such as amplitude modulation (AM) and frequency modulation (FM). Their advantages are simple implementation. Low cost Applicable for voice communication. However, the disadvantage is that it has weak anti-interference capability. Low band utilization rate. Low communication rate. Cannot meet the data communication requirements. The digital modulation stage was from the mid-20th century to the end of the 20th century. This stage mainly uses digital modulation technologies such as non-coherent modulation and coherent modulation. Their advantages are strong anti-interference capabilities. High frequency band utilization High communication rate. It can realize data communication and multi-address communication. However, the disadvantage is that it is complex to implement. High cost. High synchronous requirements. Requires cooperation with channel coding. Balanced Technologies for testing and inspection.The advanced modulation phase, spanning from the early 21st century to the present, has primarily employed new modulation technologies guided by application needs. These include Orthogonal Frequency Division Multiplexing (OFDM), Multi-Input Multi-Output (MIMO), and Space-Time Coded (STC) among others. Their advantages lie in further enhancing bandwidth utilization, communication speed, interference resistance, and coverage range. However, their implementation is more complex, costly, and demands higher channel state information requirements, necessitating the integration of technologies such as channel estimation, signal processing, and network protocols.
Modulation methods
Continuous modulation
Amplitude modulation (AM)
Frequency modulation (FM)
Angle modulation
Analog
AM (SSB, DSB)
FM
PM
Digital
ASK (OOK, QAM)
FSK (MSK, GFSK)
PSK (CPM)
Pulse-modulated
Analog
PAM, PDM, PPM
Digital
PCM, PWM
Spread spectrum
CSS
DSSS
THSS
FHSS
Figure 1. The same signal is transmitted through AM and FM.
Single-carrier underwater acoustic communication technology is a technology with significant theoretical and practical value. It plays an important role in improving the rate and reliability of underwater wireless communication, meeting the diversified needs of underwater communication.
The research on single carrier acoustic communication technology began in the 1970s, primarily using non-coherent modulation methods such as Frequency-Shift Keying (FSK). In the 1980s, with the development of digital signal processing technology, coherent modulation methods were introduced into single carrier acoustic communication, including Phase-Shift Keying (PSK) and Quadrature Amplitude Modulation (QAM). Coherent modulation methods can improve the spectral efficiency and noise resistance of acoustic communication, but they also require more complex channel estimation and equalization techniques.In the 1990s, Stojanovic and others proposed a coherent acoustic communication receiver structure based on Decision Feedback Equalization (DFE) and Digital Phase Lock Loop (DPLL), which effectively addressed the issues of time-varying acoustic channel matching and inter-symbol interference. This marked a milestone in single-carrier acoustic communication technology. Since entering the 21st century, with the increasing demand for high-speed and high-reliability in acoustic communication, frequency domain equalization techniques have been widely applied to single-carrier acoustic communication. It can effectively suppress multipath interference and noise interference, thereby enhancing the performance of acoustic communication.
The research on frequency domain equalization technology mainly includes two aspects: channel estimation and signal restoration. Channel estimation refers to the use of received signals or known training sequences to estimate the characteristic parameters of underwater acoustic channels, such as the impulse response, frequency response, and delay of the channel. There are many methods for channel estimation, including the least squares (LS), minimum mean square error (MMSE), pilot-based channel estimation, blind channel estimation, etc. The accuracy of channel estimation directly affects the performance of signal restoration, making it an important link in frequency domain equalization technology.Signal restoration refers to the use of channel estimation results to process received signals for equalization, eliminating channel distortion and restoring the original signal. There are numerous methods for signal restoration, such as zero-forcing (ZF), minimum mean square error (MMSE), maximum likelihood (ML), and Turbo equalization. The effectiveness of signal restoration depends on the accuracy of channel estimation and the complexity of the equalization algorithm. Therefore, signal restoration is another crucial aspect of frequency domain equalization technology.
Currently, research on single-carrier acoustic communication technology both domestically and internationally has achieved some results. For instance, single-carrier acoustic communication technology based on frequency division multiplexing (FDM) divides a relatively wide communication band into several subbands, inserting guard bands between each subband to eliminate inter-carrier interference. Time reversal-based single-carrier acoustic communication technology utilizes time reversal processing to merge multi-channel signals into a single channel signal, with its equivalent channel impulse response having a stable main peak, thereby avoiding noise amplification. The joint equalization and decoding single-carrier acoustic communication technology views the channel equalizer and channel decoder as a cascade structure for information exchange between them to enhance signal restoration performance.
\tFrom the above research status of single-carrier acoustic communication technology both domestic and international, Single-carrier acoustic communication technology has important theoretical and practical value in underwater wireless communication field. However, there are also some problems and deficiencies. Assuring the accuracy of channel estimation. Effect of signal restoration. Algorithms for frequency domain equalization, etc. These issues need further research and exploration. In order to provide better support and guarantee for the development and application of hydroacoustic communication technology.
1.3 Principles and characteristics of single-carrier acoustic communication technology
1.3.1 Mono-carrier acoustic communication technology
Single-carrier acoustic communication technology refers to the modulation carried out on a single carrier. FSK, PSK,  QPSK,  QAM, etc. Its advantage is that it is simple to implement. Low cost Applicable to narrow-band channels. However, the challenge is its weak interference resistance. Low frequency band utilization Low communication rate. Requires cooperation with channel coding. Balanced Technologies for testing and inspection.
The principle of single-carrier underwater acoustic communication technology is to utilize the characteristics of sound wave propagation in water. Modulate the information signal onto a carrier wave. Then sent to the receiving end through the acoustic channel. Receiver demodulates the received signal. Recover information signals. The characteristics of single-carrier acoustic communication technology are as follows.
Applicable to narrowband channels: Due to the bandwidth of underwater acoustic channels being affected by sea absorption, Restrictions due to factors such as transducer bandwidth. Usually only a few dozen to several hundred hertz. Therefore, single-carrier acoustic communication technology can be effectively transmitted on such narrowband channels. And does not require complex spectrum allocation and management.
Simple and cost-effective: Due to the single-carrier underwater acoustic communication technology only requiring one carrier, the hardware implementation at both the transmitter and receiver ends is relatively simple. There is no need for multiple oscillators, filters, amplifiers, etc., thus reducing the system complexity and cost.
1. Poor interference resistance. Low frequency band utilization Low communication rate: Due to the single-carrier underwater acoustic communication technology only using one carrier, Therefore, it is easily affected by noise in underwater acoustic channels. Multipath Due to the influence of Doppler, etc. Causes distortion and interference of signals. Reduce the quality and reliability of signals. At the same time, Due to the single-carrier acoustic communication technology can only transmit limited bit information, Therefore, the information transmission rate on the unit band is low. Cannot meet the requirements of high-speed data communication.
1.3.2ASK FSK PSK QPSK QAK  
ASK, also known as amplitude-shift keying, involves the carrier amplitude varying with the modulation signal. The simplest form is where the carrier is turned on and off in response to a binary modulation signal, which can also be referred to as ON-OFF Keying or OOK. Modulation method: A phase-locked loop (PLL) is used to implement the modulator. Modulation type: 2ASK, MASK. Demodulation method: Coherent and non-coherent methods.
FSK (Frequency Shift Keying) is a technique for modulating the carrier frequency with digital signals. It operates by switching the carrier frequency between two different values based on the two levels of the digital signal, thereby facilitating the transmission of information. The mathematical expression for FSK is:
\t  
Among them, A is the amplitude of the carrier, fc is the center frequency of the carrier, Δf is the frequency deviation of the carrier, x(t) is the digital signal with values ±1. The advantage of FSK is its strong anti-interference capability, but its disadvantage is low bandwidth utilization and low communication rate. There are several types of FSK, including binary FSK (2FSK), multi-level FSK (MFSK), continuous phase FSK (CPFSK) etc.
PSK (Phase Shift Keying) is a technique for modulating the carrier wave with digital signals, whereby the carrier phase is switched between two different values according to the two levels of the digital signal, thereby achieving the transmission of information. The mathematical expression for PSK is:
Among them, A is the amplitude of the carrier. fc is the carrier frequency. $\phi(t)$ is the phase of the carrier. The value can be either 0 or π. PSK has high frequency band utilization. High communication rate. However, it has high requirements for synchronization. Requires cooperation with channel coding and other technologies.
QPSK (Quadrature Phase Shift Keying) is a specific type of PSK (Phase Shift Keying), where the principle involves splitting the digital signal into two parts, each modulated with a different phase, and then superimposing the signals from both parts. The mathematical expression for QPSK is:
\t  
Among them, A is the amplitude of the carrier, fc is the frequency of the carrier, ϕ1(t) and ϕ2(t) are two parts of phase, which take values of 0, π/2, π, 3π/2. QPSK can transmit more bit information and improve communication rate, but its implementation is complex and requires high synchronization for the channel.
1.4 Multipath effects, intersymbol interference, and channel equalization
Multipath effect refers to the phenomenon where wireless signals, upon propagation, encounter different reflections, refraction, scattering, etc., resulting in signals arriving at the receiving end on multiple paths with varying delays and amplitudes. This multipath effect causes the spectrum of the signal to expand and distort, affecting its quality and reliability.
Intersymbol interference refers to in digital communication. Due to the signal time spread caused by multipath effects. The waveform of one coded symbol is spread over the other coded symbols. Consequently, it affects the restoration and demodulation of signals. Increase the error rate of signals. Assuming the transmitted signal is a square wave sequence, Due to multipath effects, Receivers will receive multiple copies of signals with varying delays and amplitudes. These signal copies will overlap. Formation of the received signal. Due to the time delay spread of signals. The waveform of the received signal will be broadened and distorted. Causes the boundary between code elements to be blurred. This is the manifestation of inter-symbol interference. If the receiving end is sampling and declaring at the same time. The moment of choice is inappropriate. This will lead to the occurrence of error bits.
Channel equalization is a technique used to eliminate or reduce the distortion and interference of the channel on signals. It can improve the quality and reliability of signals. Reduce the error rate of signals. The methods of channel equalization can be divided into two categories: time-domain equalization and frequency-domain equalization.
\tTime-domain equalization is a technique that processes signals in the time domain. Its principle is to utilize one or more filters. Inverse channel processing of the received signal. Thus, the channel's impact on the signal is offset. Restore the original signal. The advantage of time domain equalization is that it is easy to implement. The disadvantage is that it is insensitive to the time-varying and nonlinear characteristics of the channel. Applicable to situations with a small delay spread in the channel.
There are several methods for time domain equalization:
1. Linear Equalization: Linear equalization is a method of equalization using linear filters, based on the principle of minimizing mean square error or zero forcing criteria to design a linear filter that minimizes the error or interference in the output signal. The advantage of linear equalization is its low computational complexity; however, it cannot completely eliminate inter-symbol interference and is suitable for situations where the channel's delay spread is small.
Decision feedback equilibrium: Decision feedback equilibrium is a method of using nonlinear filters for equalization. Its principle is based on linear equilibrium. Add a feedback filter. Utilize the symbols that have been detected. Interference removal for undetected symbols. The advantage of decision feedback equalization is that it can effectively eliminate inter-symbol interference. The disadvantage is that the calculation is large. Need training sequences. Applicable to situations where the time delay spread in the channel is large.
Blind Equalization: Blind equalization is an equalization method that does not require channel information and training sequences. Its principle is to utilize some statistical characteristics of the signal. Homogeneity Higher order cumulants, etc. As a criterion for balance. Thus, the coefficients of the filter are adjusted. Optimize the quality of the output signal. The advantage of blind equalization is that it does not rely on channel information and training sequences. The disadvantage is that the convergence speed is slow. Applicable to situations with strong time-variability in the channel.
Frequency domain equalization is a technique for processing signals in the frequency domain. Its principle is to use Fourier transform. Convert the time-domain signal to the frequency domain. Then compensate the signal in the frequency domain. Improve the quality and reliability of signals. Finally, utilize the inverse Fourier transform. Convert frequency domain signals to time domain signals. The advantage of frequency domain equalization is that it is sensitive to the time-varying and nonlinear characteristics of the channel. The disadvantage is that it is complex to implement. Applicable to situations where the time delay spread in the channel is large. There are several methods for frequency domain equalization:
Frequency domain equalizer: A frequency domain equalizer is a method of inverse channel processing on the frequency domain. The principle is to multiply the signal by a compensation coefficient in the frequency domain. Thus eliminate the channel influence. Achieve undistorted transmission. The advantage of frequency domain equalizer is that it can completely eliminate inter-symbol interference. The disadvantage is that it is sensitive to noise. Need channel information. Applicable to situations with high signal-to-noise ratio.
Adaptive filter: An adaptive filter is a method of processing signals in the frequency domain. Its principle is based on the minimum mean square error criterion or constant modulus criterion. Dynamically adjust the coefficients of the filter. Thus minimize the error or interference of the output signal. The advantage of adaptive filter is its strong noise resistance. No channel information is required. The disadvantage is that it is complex to implement. Need training sequences. Applicable to situations with low signal-to-noise ratio.
Orthogonal Frequency Division Multiplexing: Orthogonal Frequency Division Multiplexing (OFDM) is a method of transmitting signals by splitting them into multiple orthogonal subcarriers. Its principle is to use discrete Fourier Transform. Convert the time-domain signal to the frequency domain. Then modulate on each subcarrier, Finally, the discrete Fourier inverse transform is used. Convert frequency domain signals to time domain signals. The advantage of OFDM is that it can effectively resist multipath effects. Improved bandwidth utilization The disadvantage is that it requires high synchronization. Requires the use of a loop prefix. Applicable to situations where the time delay spread in the channel is large.
Analysis of the characteristics of underwater acoustic channel. The channel in underwater acoustic communication refers to the medium through which sound waves propagate. It is subject to water bodies. The impact of the sea surface and the seabed. Characterized by complex spatiotemporal frequency-varying parameters. The noise level is high. The spread of the loss is serious. Bandwidth restrictions, Characterized by multipath effects and Doppler effects, etc. These characteristics pose significant challenges to the design and performance analysis of hydroacoustic communication systems.
2.1 Underwater Noise
In underwater acoustic communication systems, there is a strong background noise, which is an important factor affecting signal quality and communication performance. The sources of underwater noise include marine life, waves, ships, and human activities, each having different impacts on signals at different frequencies. The power spectral density of underwater noise is typically described using the Wenz curve, which is a function of frequency. In this project, we used the built-in wgn function in our code to generate white noise, and then passed it through an IIR filter to impart certain coloration to the noise, simulating the characteristics of underwater noise.
noise = wgn(length(signal_add_dopper), 1, 0); % Generate white noise
noise = filter(1, [1 -0.99], noise); % Through an IIR filter to make the noise have certain color tone
Figure 2. The wgn function provided by the MATLAB official website.
2.2 Propagation Loss
Underwater sound waves experience two types of losses: attenuation and diffusion. Attenuation is due to the interaction of sound waves with the water. Assimilation, Scattering and leakage, etc. Causes a decrease in acoustic energy. The attenuation increases with frequency and distance. Diffusion is caused by the reflection of sound waves at the interfaces between different media. Transmittance and scattering, etc. Causes sound energy to be dispersed. Diffusion forms include spherical diffusion in deep seas and columnar diffusion in shallow seas. Propagation loss is the sum of attenuation and diffusion. It also increases with the distance. Due to the influence of distance and seawater absorption coefficient, Expression is
\t  
This indicates that signals attenuate with increasing distance underwater, and energy loss occurs due to the absorption of sound waves by seawater. The absorption coefficient of seawater is related to frequency, temperature, salinity, and pressure, and is typically calculated using the Francois-Garrison formula, as shown below.
\t  
2.3 Bandwidth Limitation
\tThe available bandwidth for underwater acoustic communication is very limited. This directly affects the data transmission rate and the system's capacity. The bandwidth of the acoustic channel is limited by two aspects: one is the absorption of seawater, It makes the attenuation of high frequency signals faster. Therefore, underwater acoustic communication usually uses low-frequency signals. Secondly, the multipath effect of hydroacoustic channel. It causes the time-domain waveform of the signal to undergo delay spread. Therefore, underwater acoustic communication typically uses low-speed signals. The bandwidth of underwater acoustic communication is generally between several tens to thousands of hertz. Far below the bandwidth of land radio communications. This limits the data transmission capacity of hydroacoustic communication. To improve the bandwidth utilization of hydroacoustic communication, Some efficient modulation and coding techniques can be adopted. Orthogonal Frequency Division Multiplexing (OFDM), Multiple Input, Multiple Output (MIMO) Space-Time Coding (STC) and others.
2.4 Multiple Path Effects
In underwater acoustic channels, multipath effects cause significant intersymbol interference (ISI) which significantly limits the rate of information transmission. Multipath effects refer to the phenomenon where, due to reflections, refraction, and scattering by the sea surface and seabed, signals arrive at the receiving end along different paths, resulting in multiple copies with varying delays, as shown in Figure 2. This causes the time-domain waveform of the signal to expand in delay, leading to interference between adjacent symbols and reducing the signal's distinguishability. To mitigate multipath effects, underwater acoustic communication systems employ channel equalization techniques such as adaptive equalization, space-time coding, and multicarrier modulation. The goal of these channel equalization techniques is to process the received signals appropriately based on channel state information to restore the original signal.
2.5 Doppler Effect
The Doppler effect in underwater acoustic communication channels is more pronounced than in land radio communication channels, manifesting as frequency shifts and waveform compression or expansion. The Doppler effect refers to the change in signal frequency due to relative motion between the transmitter and receiver during the propagation of sound waves in water. This effect causes a displacement in the frequency domain waveform of the signal, leading to distortion and reducing the signal's recognizability. To mitigate the effects of the Doppler effect, underwater acoustic communication systems employ various Doppler compensation techniques such as Doppler estimation, Doppler tracking, and Doppler correction. The goal of these Doppler compensation techniques is to transform the received signals appropriately based on the Doppler shifts to restore the original signal.
2.6 Channel Part Code and Explanation
The code is as follows.
%% Add noise
SNR=15; % Signal-to-noise ratio (dB)
signal_add_noise = BandNoiseAdd(signal_send, SNR, b1 ,length_measure+length_GI, length_measure+length_GI+length_BS);  
%% Increase Doppler
% Doppler estimation accuracy
dup_precision1 = factor_resample(fs) / fs;  
dup_precision2 = 1 / (length_measure + 2*length_GI + length_BS);  
% Calculate the least common multiple, while also meeting the above two precision settings.
dup_precision = dup_precision1;  
% Doppler addition
m = 5;  
dup_ori= m * dup_precision;  
fs1 = fs * (1 - dup_ori);  
signal_add_dopper = resample(signal_add_noise, fs1, fs);  
%% Underwater Noise and Propagation Loss
% Examples of deep-sea noise spectra and the absorption coefficient of seawater
depth = 1000; % Depth, unit: meters
distance = 10000; % Distance, unit: meters
n = 20; % propagation loss parameter
alpha = 0.1; % Absorption coefficient of seawater
% Calculate propagation loss
TL = n * 10 * log10(distance) + distance * alpha;  
Note:
1. The code sets the signal-to-noise ratio to 15dB, frequency band to b1, and signal length to length_measure + length_GI + length_BS, where length_measure is the length of the measurement sequence, length_GI is the length of the guard interval, and length_BS is the length of the pilot sequence.
2. The Doppler effect in underwater acoustic communication systems is simulated, which is caused by the relative motion between the transmitter and receiver, leading to a change in signal frequency. The code uses the resample function, an internal function for resampling signals to change their sampling rate. Set the Doppler shift to m * dup_precision, where m is an integer and dup_precision is the least common multiple that simultaneously meets the Doppler estimation precision of the resampling function and the physical resolution of the FFT's Doppler precision.M is set to 5, and dup_precision is factor_resample(fs) / fs. Factor_resample calculates the greatest common divisor of the resample function, and fs is the sampling rate of the signal. The resampled sampling rate, fs1, is equal to fs * (1 - dup_ori), where dup_ori is the Doppler shift.
3. The code takes into account underwater noise and propagation losses, utilizing the wgn function, which is an internally defined function for generating white noise and setting its length to the length of signal_add_dopper. The signal is filtered using a filter function, employing an IIR filter with a first-order design, where the numerator coefficients are set to 1 and the denominator coefficients are [1 -0.99], thus allowing the noise to have certain color characteristics to simulate the characteristics of underwater noise.The power of noise was also adjusted according to propagation loss. The formula for propagation loss is TL = n * 10 * log10(distance) + distance * alpha, where n is the propagation loss parameter, distance is the distance, and alpha is the absorption coefficient of seawater. For this scenario, assuming a depth of 1000 meters and a distance of 10000 meters, with n set to 20 and alpha to 0.1.
3.1 System Simulation Parameters
Simulation parameters
Parameter value
Simulation parameters
Carrier frequency f
12 kHz
Communication bandwidth B
4000 Hz
Sampling rate f
48 kHz
Synchronization signal
LFM/50ms
Number of bits N sent
2000
Guard interval
50ms
Code symbol width Ts
0.5ms
Roll-off factor a
1

3.2 Adding and Decoding Noise
Adding noise refers to the process of transforming the original binary data at the transmitter into data with certain desired characteristics, such as DC balance, conversion density, and anti-interference capabilities. The method of adding noise typically involves using a pseudorandom sequence (such as an m sequence or Gold sequence) to perform XOR operation with the data to generate the noisy data. Decoding noise refers to the process of restoring the original data from the noisy data received at the receiver by performing an inverse XOR operation with the same pseudorandom sequence used at the transmitter. The purpose of adding and decoding noise is to enhance the quality and reliability of the signal, preventing it from being affected by noise, Doppler effects, propagation losses, etc. during transmission.
In this project code, the functions for scrambling and de-scramble use a method based on Linear Feedback Shift Register (LFSR), also known as m-sequence scrambling and de-scramble. The principle of this method is to utilize a shift register of length m, where each bit is a flip-flop that can store either 0 or 1. The output of the shift register is the value of the last bit, and the input to each bit is the XOR operation between the output of the previous bit and some bits. The positions of these bits are determined by a feedback function, such as. Thus, in each clock cycle, the content of the shift register moves one position to the right and produces a new output. If the feedback function is chosen appropriately, the shift register can produce a pseudorandom sequence with a loop length of 2m-1, also known as the m-sequence.This sequence exhibits good statistical properties, such as an even distribution of 0s and 1s, low autocorrelation, and high cross-correlation. We chose m=15 and employed it as a feedback function. The msig vector in the code represents the initial state of the shift register, which is the values of the 15 flip-flops from high to low. The scrambling function involves XORing the msig vector with the input signal to produce the scrambled signal. The de-scrambling function does the same but with the scrambled signal and the msig vector to produce the de-scrambling signal. Since XOR operations are reversible, scrambling and de-scrambling can be reversed, meaning that the original signal can be restored through two XOR operations.
Figure 3. Comparison of the scrambled signal
3.3 Coding and Decoding
Encoding refers to the process of mapping the original binary data at the sender end, enabling it to be modulated on a carrier. There are various methods of encoding, such as BPSK, QPSK, and 8PSK, differing in the number of bits each symbol can carry and the phase changes involved. The purpose of encoding is to enhance the spectral efficiency and resistance to interference of the signal, allowing it to transmit more information within a limited bandwidth. Decoding involves making certain decisions at the receiving end regarding the modulated signal, restoring the original data. The method of decoding typically relies on comparing the amplitude and phase of the signal with the mapping table sent by the sender, identifying the closest symbol, and then obtaining the corresponding data. The goal of decoding is to accurately demodulate the signal and restore the original information.
3.3.1 QPSK  
QPSK is a modulation technique that utilizes phase shifts to transmit data, capable of carrying two bits per symbol, thereby enhancing spectral efficiency. QPSK has four possible phase shifts: 45°, 135°, 225°, and 315°, each corresponding to a binary code group, such as 00, 01, 10, and 11. Thus, each symbol can represent one of these four states.
To generate a QPSK signal, we can use the I/Q modulation method, which involves multiplying two orthogonal carriers with the signals on the I and Q paths respectively, and then adding them to obtain the QPSK signal. The signals on the I and Q paths are obtained by mapping and pulse shaping the original binary data. For example, if our mapping scheme is 00 corresponding to 1, 01 corresponding to -1, 10 corresponding to j, and 11 corresponding to -j, we can derive the following signals for the I and Q paths:
Among them, h(t) is the symbol after mapping, p(t) is the impulse response of pulse-shaped filter, T is the symbol period, fc is carrier frequency. So, QPSK signal can be expressed as:
Among them, is the plural symbol, which can be represented as , where is the phase angle, which determines the state of the QPSK signal. For example, when , corresponds to the 00 code group; when , corresponds to the 01 code group, and so on. To demodulate a QPSK signal, we can use coherent demodulation methods, which involve multiplying the received signal with a synchronized local carrier, then passing through a low-pass filter to obtain the I and Q signals, followed by decision-making and decoding to restore the original binary data. For instance, if our local carrier is , we can obtain the following I and Q signals:
Among them, LPF denotes a low-pass filter. It is evident that I and Q are identical, only differing by undergoing one pulse shaping filter. Therefore, we can make decisions on the sampling points of each symbol for I and Q, obtain , and then use the mapping method to derive and, ultimately obtaining the original binary data.
Certainly, channel effects must also be considered, such as noise, Doppler shift, and propagation loss, which can cause distortion and interference in the received signal, thereby affecting the performance of demodulation. To enhance the accuracy and robustness of the demodulation process, we need to employ signal processing techniques, such as bandpass filtering, Doppler compensation, equalizers, etc. The code also utilizes four different types of equalizers: LMS, RLS, MMSE, and DFE. Their objective is to adjust the amplitude and phase of the received signal to counteract the distortion caused by the channel, thus bringing the signal closer to its original symbols.
3.3.2 Code Results
Figure 4.1 Results One
Figure 4.2 Results, Part Two
Figure 4.3 Results Three
3.4 Pulse shaping
Pulse shaping refers to the process of filtering the encoded signal at the transmitter to ensure it has a certain waveform and spectral characteristics. There are various methods for pulse shaping, such as rectangular pulses, raised cosine pulses, and root raised cosine pulses, among others. The differences lie in the duration of the pulse, main lobe width, and sidelobe height. The purpose of pulse shaping is to reduce the interference in the time domain and frequency domain of the signal, such as intersymbol interference and spectral leakage, allowing for clearer signals to be transmitted within limited time and frequency ranges. In this project code, for the transmitter part, a root raised cosine pulse shaping filter was generated using the rcosdesign function, followed by pulse shaping and carrier modulation of the signal using the IQmodulate function; for the receiver part, you used the IQdemodulate function to perform carrier demodulation and pulse shaping filter matching filtering of the pulse shaping filter.
Figure 5: Pulse-forming results
3.5 Time Synchronization
Time synchronization refers to the process of extracting time-related information from received modulated signals at the receiving end, and then continuously adjusting the local carrier signal's frequency, phase, or pulse position to align it with the carrier signal transmitted by the sender. There are various methods for time synchronization, such as Phase Locked Loop (PLL), Costas algorithm, Gardner algorithm, etc. The difference lies in the precision, speed, and complexity of synchronization. The purpose of time synchronization is to achieve coherent demodulation, enhancing the accuracy and robustness of decoding. In this project, at the receiving end, cross correlation between the measured signal and its replica is used to obtain two peaks, corresponding to the beginning and end of the signal. Based on the positions of these peaks, the modulated signal segment within the signal can be extracted, thereby achieving time synchronization.
\t  
Figure 6 Time synchronization results
3.6 Doppler Estimation and Compensation
Doppler estimation is based on the measurement signal segments at the beginning and end of the signal. Calculate the length changes of received and transmitted signals. Thus, a rough estimate of the Doppler factor is obtained. Then, Extract a single frequency signal segment from the signal. Perform a fast Fourier Transform on it. Determine the frequency corresponding to the maximum amplitude. At this frequency, Frequency spectrum refinement using Chirp-Z transform. Get a more accurate frequency estimate. Finally, Utilizing the spectral correction method. Eliminate frequency errors. A refined estimate of the Doppler factor is obtained.
The ratio of the lengths of received and transmitted signals, which is a rough estimate of the Doppler factor, where _ is the length of the transmitted signal and _ is the length of the received signal.
The frequency corresponding to the maximum amplitude of a single-frequency signal segment. A rough estimate of Doppler shift. Among them, fs is the sampling frequency. Y(k) is the discrete Fourier transform of a single-frequency signal segment. N is the number of points in the Fourier transform:
\t  
Utilize Chirp-Z transformation for spectral fine-tuning to obtain more precise frequency estimation values. Here, the sum is the range of spectral fine-tuning, and the result of the Chirp-Z transformation is denoted as .
\t  
Utilize the spectral correction method to eliminate frequency errors, obtaining a precise estimate of the Doppler factor. Here, is the frequency correction value, and is the frequency of the single-frequency signal:
\t  
Doppler compensation involves re-sampling the received signal based on estimated Doppler factors to restore its original sampling rate, thereby eliminating the effects of Doppler shift on the signal.
\t  
Among them, is the signal before Doppler compensation, is the signal after Doppler compensation, and is the estimated value of the Doppler factor.
\t  
Figure 7 Doppler supplementary results
\t  
Time-domain equalization 4. Time-domain equalization
A time-domain equalizer is a filter used to correct or compensate for the distortion and intersymbol interference in a signal within a channel. The principle of the time-domain equalizer is to adjust the weight coefficients of the filter. Minimize the error in receiving signals. Thus, the original waveform of the signal is restored. The time-domain equalizer can be divided into linear equalizer and nonlinear equalizer. The linear equalizer only uses the feedforward information of the received signal. The nonlinear equalizer also utilizes feedback information from the decision signal.
The role of time-domain equalization in this project is to counteract the multipath effects and frequency selective fading of hydroacoustic channels, thereby enhancing the quality and performance of signals. Four types of time-domain equalizers were utilized in this project: LMS, RLS, MMSE, and DFE.
4.1 LMS  
\tLeast Mean Square (LMS) is an iterative optimization algorithm based on gradient descent, which continuously updates the weight coefficients to minimize the mean square error of the error. The output of the LMS equalizer can be represented as: where y(k) is the output of the equalizer at time k, x(k) is the input of the equalizer at time k, h(l) is the weight coefficient of the equalizer, and n is the length of the equalizer.
\t  
The error of the LMS equalizer can be represented as, where d(k) is the desired signal, which is a copy of the transmitted signal:
\t  
The weight update formula of LMS equalizer can be represented as follows: where, μ is the learning rate, which determines the speed and stability of weight update.
\t  
4.2 RLS  
\tRecursive Least Squares (RLS) is an iterative optimization algorithm based on the least squares method, aiming to minimize the sum of squared errors. The output and error of the RLS equalizer are the same as those of the LMS equalizer, but the weight update formula differs. The weight update formula for the RLS equalizer can be represented as:
Among them, is the gain matrix, which can be represented as: where, is the covariance matrix, which can be represented as: is the forgetting factor, which determines the degree of historical data affecting the current weights.
4.3MMSE  
\tMinimum Mean Square Error (MMSE) is an acronym for Minimum Mean Square Error, which is a balanced algorithm based on optimal linear estimation. It solves the Wiener-Hoff equation to obtain the weight coefficients that minimize the mean square error of the error. The output and error of the MMSE equalizer are the same as those of the LMS equalizer, but the weight coefficients do not need to be updated iteratively; instead, they are directly solved. The weight coefficients of the MMSE equalizer can be represented as: the autocorrelation matrix of the input signal, p is the cross-correlation vector between the input signal and the desired signal.
4.4DFE  
The Decision Feedback Equalizer (DFE) is a type of nonlinear equalizer, consisting of a feedforward filter and a feedback filter. The feedforward part can eliminate leading interference, while the feedback part can counteract trailing interference. The output of the DFE can be represented as the weight coefficients of the feedforward filter, the weight coefficients of the feedback filter, and the decision signal:
\t  
\tThe error of DFE equalizer can be represented as:
\tThe weight update formula of DFE equalizer can be represented as:
\t  
4.5 Time-domain equalization results
After running the complete program, you will get...
\t  
MATLABCode%% Doppler Detection and Compensation\nclc;\nclear all;\nclose all;\n% Global image drawing settings\n% set(0, 'defaultfigurecolor', 'w') % Draw background as pure white\n% set(0, 'defaultAxesFontSize', 12) % Set the font size of the drawing coordinate axis to 12\n% set(0, 'defaultAxesTitleFontSizeMultiplier', 1.2) % Set the font size of the plot title to 16\n% set(0, 'defaultAxesFontName', 'Song Semibold') % Modify the default font\n% set(0, 'defaultAxesLineWidth', 1) % modify the default frame line thickness\n% set(0, 'defaultLineLineWidth', 1.2);% modify the default line thickness\nset(0, 'defaultAxesXGrid','on', 'defaultAxesYGrid', 'on') % Open the grid\n%% Mode selection\nMOD = 'mo_qpsk';                                                   % Different mapping methods can be selected, such as bpsk, qpsk, and 8psk.\nswitch (MOD)\n    case 'mo_bpsk', Mod = 2; bitnum_per = 1;\n    case 'mo_qpsk', Mod = 4; bitnum_per = 2;\n    case 'mo_8psk', Mod = 8; bitnum_per = 3; \n    otherwise, disp('Unknown signal constellation!');\nend\n​\n%% Basic Parameters\nfs = 100e3;                                                            % Sampling frequency\nfl = 8e3;                                                                 % Lower frequency limit\nfh = 12e3;                                                              % Upper frequency limit\nf0 = (fl + fh) / 2;                                                        % Center frequency (single-band transmission)\nRb = 2000;                                                             % Signal rate\nN_up = fs / Rb;                                                        % Increase the number of sampling points\nN_BS = 3000;                                                           % Number of symbols sent\nlength_BS = N_BS * N_up;\nN_bit = N_BS * bitnum_per;                                             % The number of bits to be generated\nalpha = 1;                                                              % Rolling down coefficient\nN_filter = 512;                                                        % Filter order\nPulseShape = rcosfir(alpha, [ ], N_up, 1, 'sqrt');  % Impulse-shaped filter (Low-pass filter)\nb1 = fir1(N_filter, 2 * [fl fh] / fs);                               % Bandpass filter\n​\n%% --------------------Transmitter Section-------------------------\n%% Data signal generation and encoding\nload information.mat\nbit_send = information(1 : N_bit);            \n​\n%% Information Mapping\n[SymbolIn, Table] = Mapping(bit_send, Mod);   \n​\n%% IQ modulation pulse shaping up-sampling and carrier\nsignal_IQ = IQmodulate(PulseShape, N_up, SymbolIn, f0, fs);\nsignal_IQ = signal_IQ ./ max(abs(signal_IQ));\n%% Doppler Measurement Signal (LFM)\nT_syn = 0.1; B = fh - fl; K = B / T_syn;                              %LFM signal parameters, B bandwidth, T pulse width, K modulation slope\nt = 0 : 1/fs : T_syn-1/fs;\nsignal_measure = cos(2*pi*fl*t + pi*K*t.^2);                  \nlength_measure = T_syn * fs;\nlength_GI = 0.1 * fs;                                                % Protective interval\nsignal_GI = zeros(1, length_GI);\n​\n%% Signal transmission configuration\nsignal_send = [signal_measure signal_GI signal_IQ signal_GI signal_measure signal_GI];    % Signal structure [Measurement signal, Protection interval, Modulation signal, Protection interval, Measurement signal, Protection interval]\n​\n%% --------------------Channel Section------------------------\n%% Adding noise\nSNR=15;                                         % Signal-to-noise ratio (dB)\nsignal_add_noise = BandNoiseAdd(signal_send, SNR, b1 ,length_measure+length_GI, length_measure+length_GI+length_BS);\n% signal_add_noise=signal_send;\n​\nMATLABSimulation results  

## Images

![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](01.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](02.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](03.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](04.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](05.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](06.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](07.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](08.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](09.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](10.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](11.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](12.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](13.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](14.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](15.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](16.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](17.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](18.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](19.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](20.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](21.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](22.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](23.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](24.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](25.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](26.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](27.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](28.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](29.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](30.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](31.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](32.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](33.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](34.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](35.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](36.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](37.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](38.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](39.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](40.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](41.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](42.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](43.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](44.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](45.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](46.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](47.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](48.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](49.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](50.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](51.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](52.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](53.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](54.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](55.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](56.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](57.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](58.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](59.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](60.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](61.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](62.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](63.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](64.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](65.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](66.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](67.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](68.jpg)
![Study on Single-Carrier Acoustic Communication Technology [with MATLAB Code]](69.jpg)

<!-- PAYMENT_BLOCK -->

## Get this dataset

- Payment link (Stripe): [Buy now](https://buy.stripe.com/3cs8yP7sY87d0vu9AB)
- Payment QR code: ![Payment QR code](pay.png)

<!-- /PAYMENT_BLOCK -->
