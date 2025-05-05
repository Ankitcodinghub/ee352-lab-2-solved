# ee352-lab-2-solved
**TO GET THIS SOLUTION VISIT:** [EE352 Lab 2 Solved](https://www.ankitcodinghub.com/product/ee352-lab-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94331&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EE352 Lab 2 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
<div class="layoutArea">
<div class="column">
1 Preliminaries

In this week, we review the ”filtering” subject which was previously covered in Signals &amp; Systems lectures. In communication systems, filters are widely used to demodulate the received signals in the receivers. Filters can be examined in four categories which are low pass, high pass, band pass and band stop filters. These filters pass or reject the signals according to the cut-off frequencies in frequency domain. An ideal filter has a sharp frequency response which does not pass the frequency components of the signals beyond the desired cut-off frequency. For example, ideal low pass filters only pass the frequency components between 0 Hz and the determined cut-off frequency or ideal band pass filters only pass the signals between the desired two frequencies. Nonideal filters do not have a sharp frequency response and have a transition band around the cut-off frequency. This transition band can cause to have undesired frequency components. The filtering operation can be accomplished by multiplication in frequency domain.

For this week’s experiment, it is useful to remember the functions that are employed in Week-1’s experiment. Furthermore, it is also useful to learn about the Matlab functions find(.), butter(.), freqz(.) and filter(.) by using Matlab Help before doing the labwork given below.

In your reports, the details of the plots should be visible. Do not take screenshots to copy the figures plotted in Matlab. Instead, after plotting a Figure in Matlab, apply the following steps to copy the figure: Figure Window −− &gt; Edit −− &gt; Copy Figure.

2 Labwork

Read the preliminaries given above carefully before doing the experiment given below. You must show the negative part of the frequency spectrum in your figures.

</div>
</div>
<div class="layoutArea">
<div class="column">
2.1

a.

b.

</div>
<div class="column">
Construction of the Signals

Construct x2(t) = cos(120πt)+cos(500πt) where the sampling frequency fs = 1000 Hz and its duration is 2 s. Obtain the Fourier transform of x2(t) where the number of DFT points (N) is the length of the signal.

The magnitude of the frequency spectrum of x(t), i.e., |X(f)|, is given in Fig. 1. Construct |X(f)| which is a triangular signal between −50 Hz and 50 Hz. Hint: You can use find(.) function in Matlab to find and change the nonzero components of the signal.

</div>
</div>
<div class="layoutArea">
<div class="column">
1

0.8

0.6

0.4

0.2

0

-500 -400

</div>
<div class="column">
-300 -200 -100 0 100 f (Hz)

</div>
<div class="column">
200 300 400 500

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
|X(f)|

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 1: The plot of |X(f)|.

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
EE 352 – Lab 1: Signals &amp; Systems Review

</div>
</div>
<div class="layoutArea">
<div class="column">
c. Generate the signal |Y1(f)| by using the relation |Y1(f)| = |X(f)| + |X2(f)|.

d. Plot |X(f)|, |X2(f)| and |Y1(f)| in the same figure (by using subplot(3,1,.) command) where x-axis

shows the frequency in Hz.

2.2 Filtering

<ol>
<li>As shown in Fig. 2, filter |Y1(f)| with an ideal low pass filter, which has the frequency response H1(f), to obtain the nonzero frequency components of |X(f)|.
Figure 2: Block diagram of the filtering operation for H1(f).
</li>
<li>Plot |H1(f)| and the filtered signal |Y2(f)| in the same figure (by using subplot(2,1,.) command) where
x-axis shows the frequency in Hz.
</li>
<li>As shown in Fig. 3, filter |Y1(f)| with an ideal band pass filter, which has the frequency response H2(f), to obtain the frequency components of |X2(f)| stemming from cos(500πt). Hint: Do not forget to filter the negative frequency components!
Figure 3: Block diagram of the filtering operation for H2(f).
</li>
<li>Plot |H2(f)| and the filtered signal |Y3(f)| in the same figure (by using subplot(2,1,.) command) where
x-axis shows the frequency in Hz.
</li>
<li>Using butter(.) function, design a nonideal band pass filter, which has the frequency response Hbpf(f) to obtain the frequency components of |X2(f)| stemming from cos(500πt). Filter x2(t) with Hbpf(f) as shown in Fig. 4.
Figure 4: Block diagram of the filtering operation for Hbpf(f).
</li>
<li>Plot |Hbpf(f)| and the filtered signal |Ybpf(f)| in the same figure (by using subplot(2,1,.) command) where x-axis shows the frequency in Hz. You can use freqz(.) function which does not show the negative part of the frequency spectrum to plot only the filter response.</li>
</ol>
</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Y1(f)

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
H1(f)

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Y2(f)

</div>
</div>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Y1(f)

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
H2(f)

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Y3(f)

</div>
</div>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
x2(t)

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Hbpf(f)

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Ybpf(f)

</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
