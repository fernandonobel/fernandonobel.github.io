---
title: "Sample Raw Markdown from the Python-MATLAB Interoperability Workshop"
---

# Sample Raw Markdown from the Python-MATLAB Interoperability Workshop

---

```
## Why do we want to develop a toolbox? 

We want a toolbox to:

  - **accesibilize** the use of techniques
  - develop and try new ideas **faster**
  - **colaborate** better together.

## What is a useful tool?

A good tool:

  - solves one specific problem
  - uses a software-independent standard for its inputs and outputs
  - has enough documentation and examples.

## Example of a really good tool: STRIKE-GOLDD

\begin{columns}
  \begin{column}{0.5\textwidth}
  The STRIKE-GOLDD toolbox:
  
  \begin{itemize}
    \item is a free and open-source
    \item does identificability and observability analysis
    \item avoids bad surprises
  \end{itemize}
  
  \end{column}
  
  \begin{column}{0.5\textwidth}
  \begin{figure}
  \centering
  \includegraphics[width=\columnwidth]{img/strike_goldd_paper}
  \end{figure}
  
  \end{column}
\end{columns}

## {.standout}

Do you always use STRIKE-GOLDD \
before running an identification? Why?

## The Python vs. MATLAB dilemma

Not using STRIKE-GOLDD is a huge opportunity cost!

Not using software-independent standards leads to...

  - ineficient workflows that promote reinventing the wheel
  - the Python vs. MATLAB dilemma
 
## Example

::: columns

:::: column
We developed a data-driven method which:

  - infers the structure of a model from experimental data
  - but requires the measurement derivatives

\vspace{0.5cm}

There are many methods to approximate derivatives:

  - PyNumDiff is a Python package that implements many of them
 
::::

:::: column
\begin{figure}
\centering
\includegraphics[width=\columnwidth]{img/paper}
\end{figure}
::::

:::

## Two options

\centering

**Option 1: Do everything in Pyton**

[![](https://mermaid.ink/img/pako:eNqNUkuPmzAQ_ivIp21EIswrC6r2Uo7dNmpuhR4cPAQr2EbGbkuj_PcOr2p7qYoveOZ7-LPnTmrNgeSkUk2nf9QtM9b7-KVSlfLwG9zlaljfervdabStVrudt3S4MFBbodWMnipFUD6dLbOwH3pWg_f-Yl48ierdu28L4kTLs5CuQ8zSHUZlW7Ci9jizbENF5Wdn5sqeG_Ed1CoFeAA-gVY_Wj69AhucAQnKDptLEf5VX8gcUIlZVJtxq1NYnsZPThaiaVYyKD511_R27ABzeY3ourwX6uYP1ugb5JeO1be3oBP9H1D0T9Bmi4b7_QtKbrc2bwu6xV664ZZh6YZb-KUbLSneLuKTqxGc5NY48IkEI9m0JfeJWhF8CQkVyfGXQ8NcZyucigfSeqa-ai03ptHu2pK8Yd2AO9fjS0EhGA6K_FM1eJFgPminLMlpFs0iJL-TnyRPo0NKkywOgizKspjGPhkRlAaHOEyOQZwlaZDEx4dPfs2uweH5mYZhGmdRckzoMUUCc1afR1VvZwIurDavyyzPI_34DXY84zc?type=png)](https://mermaid.live/edit#pako:eNqNUkuPmzAQ_ivIp21EIswrC6r2Uo7dNmpuhR4cPAQr2EbGbkuj_PcOr2p7qYoveOZ7-LPnTmrNgeSkUk2nf9QtM9b7-KVSlfLwG9zlaljfervdabStVrudt3S4MFBbodWMnipFUD6dLbOwH3pWg_f-Yl48ierdu28L4kTLs5CuQ8zSHUZlW7Ci9jizbENF5Wdn5sqeG_Ed1CoFeAA-gVY_Wj69AhucAQnKDptLEf5VX8gcUIlZVJtxq1NYnsZPThaiaVYyKD511_R27ABzeY3ourwX6uYP1ugb5JeO1be3oBP9H1D0T9Bmi4b7_QtKbrc2bwu6xV664ZZh6YZb-KUbLSneLuKTqxGc5NY48IkEI9m0JfeJWhF8CQkVyfGXQ8NcZyucigfSeqa-ai03ptHu2pK8Yd2AO9fjS0EhGA6K_FM1eJFgPminLMlpFs0iJL-TnyRPo0NKkywOgizKspjGPhkRlAaHOEyOQZwlaZDEx4dPfs2uweH5mYZhGmdRckzoMUUCc1afR1VvZwIurDavyyzPI_34DXY84zc)

**Option 2: Do everything in MATLAB**

[![](https://mermaid.ink/img/pako:eNpVUsuO2zAM_BWDp93ACfxOLBQLbNfHDVo0PdXeg2IxsRBZMmSpbRrk3yu_itS6mORwZkjpBrViCAQqeRLqV91Qbbz3b5WspOe-3h7PmnaNt1rtX7-_v35eraYC4xprw5UcwUOmCMqng6EG131Ha_Q-HfWL1zpy8fwxIb6G5YG3VjjMVO2v0jRoeO0xauiCissvVo-ZNdP8J8qZCk2j2ACa9cLyaY-0txpblKZfVIrov_zUzNAxUePYRtysFJVvVNQPhh5gMxtKNsDnbZirQNfmnbgQpOPy4vdGqwuSo6D1ZYEVgbdev7hxl7HHsAgX31M1WkxM1WhxP1XjSfXxgA9nzRkQoy360KJu6RDCbWitwK2yxQqI-2V4olaYyt3q3bV1VP5Qql06tbLnBsiJit5FtnOrxoJTd9Htv6x2g6N-U1YaIFG6HUmA3OA3kCzeZGGaJ0GQx3mehIkPVyBhFmwShwySPM2CNNneffgzqgab3S6MoizeZVm8zaI09IFaow5XWS-ekHGj9H56i-OTvP8FtRTNwQ?type=png)](https://mermaid.live/edit#pako:eNpVUsuO2zAM_BWDp93ACfxOLBQLbNfHDVo0PdXeg2IxsRBZMmSpbRrk3yu_itS6mORwZkjpBrViCAQqeRLqV91Qbbz3b5WspOe-3h7PmnaNt1rtX7-_v35eraYC4xprw5UcwUOmCMqng6EG131Ha_Q-HfWL1zpy8fwxIb6G5YG3VjjMVO2v0jRoeO0xauiCissvVo-ZNdP8J8qZCk2j2ACa9cLyaY-0txpblKZfVIrov_zUzNAxUePYRtysFJVvVNQPhh5gMxtKNsDnbZirQNfmnbgQpOPy4vdGqwuSo6D1ZYEVgbdev7hxl7HHsAgX31M1WkxM1WhxP1XjSfXxgA9nzRkQoy360KJu6RDCbWitwK2yxQqI-2V4olaYyt3q3bV1VP5Qql06tbLnBsiJit5FtnOrxoJTd9Htv6x2g6N-U1YaIFG6HUmA3OA3kCzeZGGaJ0GQx3mehIkPVyBhFmwShwySPM2CNNneffgzqgab3S6MoizeZVm8zaI09IFaow5XWS-ekHGj9H56i-OTvP8FtRTNwQ)

## {.standout}

What would you do?

Option 1: Do everything in Python

Option 2: Do everything in MATLAB

## {.standout}

What would you do?

Option 1: Do everything in Python $\rightarrow$ not use MATLAB

Option 2: Do everything in MATLAB $\rightarrow$ not use PyNumDiff

## There is a third option

\begin{columns}

  \begin{column}{0.5\textwidth}
    \textbf{Option 3: Use MATLAB and Python}
    \vspace{0.5cm}
    Use a file that can be read and written by:
    \begin{itemize}
      \item MATLAB
      \item Python
    \end{itemize}
    \vspace{0.5cm}
    We used CSV (comma-separated value)
  \end{column}
  
  \begin{column}{0.5\textwidth}
    \begin{figure}
    \centering
    \includegraphics[width=\columnwidth]{img/csv_example}
    \end{figure}
  \end{column}

\end{columns}

## The workflow we used

\centering

[![](https://mermaid.ink/img/pako:eNptUltvmzAU_ivoPHVREtmGkIKmSl15bLZomfYw6IOLDwEJ25Gxt7Eo_30u1Kkq1bz4XL7LOfgMtRYIOVSq6fWfuuXGRo_fK1WpyJ_BPR8NP7XRYrG7__F4_2WxmAsFKW8OlltcDSdeY_T52dxF0lP1n57mjj0tD510ve-Zq8OobIu2qyPBLQ9dcfnNmSmzEqb7jeqVCm2rxWsTKvGBoYfDz6jpehyunmh5s0M-OIMSlR2Ck4K9y88CAr0at17x2vexzH70TlTQ2LNyP351suia5j0sQAsSrVZ3fvywhiksaPA4V1mgm6ssOJ2rcSB8-2AJR9MJyK1xuASJRvKXEM4v0Ar8aiVWkPurwIa73lb-n1487MTVL61lQBrtji3kDe8HH7mTXz0WHffjymvW-JnQPGinLOQsySYSyM_wF_I0Xqd0kyWEZHGWJTRZwgg5Tck6YZstSbJNSjbJ9rKEf5MqWd_eUsbShLCYpluaejburD6Mqg6eUHRWm938EqcHefkPmEXKNQ?type=png)](https://mermaid.live/edit#pako:eNptUltvmzAU_ivoPHVREtmGkIKmSl15bLZomfYw6IOLDwEJ25Gxt7Eo_30u1Kkq1bz4XL7LOfgMtRYIOVSq6fWfuuXGRo_fK1WpyJ_BPR8NP7XRYrG7__F4_2WxmAsFKW8OlltcDSdeY_T52dxF0lP1n57mjj0tD510ve-Zq8OobIu2qyPBLQ9dcfnNmSmzEqb7jeqVCm2rxWsTKvGBoYfDz6jpehyunmh5s0M-OIMSlR2Ck4K9y88CAr0at17x2vexzH70TlTQ2LNyP351suia5j0sQAsSrVZ3fvywhiksaPA4V1mgm6ssOJ2rcSB8-2AJR9MJyK1xuASJRvKXEM4v0Ar8aiVWkPurwIa73lb-n1487MTVL61lQBrtji3kDe8HH7mTXz0WHffjymvW-JnQPGinLOQsySYSyM_wF_I0Xqd0kyWEZHGWJTRZwgg5Tck6YZstSbJNSjbJ9rKEf5MqWd_eUsbShLCYpluaejburD6Mqg6eUHRWm938EqcHefkPmEXKNQ)

## We avoid the opportunity cost

With this workflow, we:

  - use MATLAB for (almost) everything
  - only need to know the bare minimum of Python:
    - how to load and save a CSV
    - how to use PyNumDiff

The advantages:

  - we avoid the opportunity cost
  - we solve the Python vs. MATLAB dilemma
  - the workflow is flexible

## We can easily use real experiment data

\centering

[![](https://mermaid.ink/img/pako:eNptUsGOmzAQ_RU0p21EIuMQAqhaabscNy3aVD0UevDiISCBQcZul0b59zp4HWnVtS_2vDfz3nh8hmrgCCmUou6GP1XDpPKenktRCs-sSb-cJBsbb7U6PHx_eviyWlkgI8XdUTGF62lkFXqfX-S915tS3adflpEHxbHtdWc4Fp1moRpUbeVxpphjbYtvWi6RNZftbxRvpVA1A38joeAfGHo8_vDqtsPp5iko7g7IJi2xR6Em5ySj7-JWgKNRY8oo3ngfy-SzcSKcRk6LfP6q-6yt6__T8rB4RtZZBXwdjcZV0fUaeuv1vbHp6BlZAnngXuyG23YsSp2yRalryqLba7H3G3w4yZZDqqRGH3qUPbte4XxNLcFMoccSUnPkWDPdqdKM_2LSRiZ-DkPvMuWgTw2kNesmc9OjmRJmLTMv09-i0rSP8nHQQkFK42QpAukZXiGNtpso2CUhIck2ScIg9GGGNIjIJqS7PQmTXUR24f7iw99FlWziOKA0oiSO6Z6YNB-YVsNxFpXzhLxVgzzYT7v83cs_bCDWYA?type=png)](https://mermaid.live/edit#pako:eNptUsGOmzAQ_RU0p21EIuMQAqhaabscNy3aVD0UevDiISCBQcZul0b59zp4HWnVtS_2vDfz3nh8hmrgCCmUou6GP1XDpPKenktRCs-sSb-cJBsbb7U6PHx_eviyWlkgI8XdUTGF62lkFXqfX-S915tS3adflpEHxbHtdWc4Fp1moRpUbeVxpphjbYtvWi6RNZftbxRvpVA1A38joeAfGHo8_vDqtsPp5iko7g7IJi2xR6Em5ySj7-JWgKNRY8oo3ngfy-SzcSKcRk6LfP6q-6yt6__T8rB4RtZZBXwdjcZV0fUaeuv1vbHp6BlZAnngXuyG23YsSp2yRalryqLba7H3G3w4yZZDqqRGH3qUPbte4XxNLcFMoccSUnPkWDPdqdKM_2LSRiZ-DkPvMuWgTw2kNesmc9OjmRJmLTMv09-i0rSP8nHQQkFK42QpAukZXiGNtpso2CUhIck2ScIg9GGGNIjIJqS7PQmTXUR24f7iw99FlWziOKA0oiSO6Z6YNB-YVsNxFpXzhLxVgzzYT7v83cs_bCDWYA)

## We can easily add more tools

\centering

[![](https://mermaid.ink/img/pako:eNp9U11vmzAU_SuWn7qIRHwmAU2VuvI0NR1qpj0M9uDgS0ACGxl7DYvy3-fgGKlVVXjB95xz7_HBPuOSU8AJLljV8teyJkKip5eCFQzpZ1CHoyB9jRaL3cPPp4dvi4UBUje_20siYTn0pAT09SDuUadbtV_-GEbm5fumU63mGHQYmaxBNiWiRBLLCvIfSkyVJRXNX2C3ViBrTm8kYPQDQ9moKcwayvw8G59VlzZV9ansu2obMqui_BleEWEUVYSVoxkuOW8P_PRpm8f9L1Q1LQxzIl5-twMyKAEdMDnYHFL_Td1MoKD3SqTe78ybxlw_bs7C_AVIa-hw6rXgKrexhWi5vNczrbPUnQqZZ8OfcePNoL7NyqC-dWjQ4C05mknvX-zgo2goTqRQ4OAOREeuS3y-diiw_s0dFDjRnxQqolpZ6PN10bKesN-cd1YpuDrWOKlIO-iV6vUxgLQhOuNurgodDIhHrpjESRRspiY4OeMTTtbBau1Fcei6cRDHoRc6eMSJt3ZXoR9t3DCO1m4Ubi4O_jdNdVfbref7az-IQtf3t_HWwURJvh9ZaT0BbSQXO3Mrpstx-Q-pbfHF?type=png)](https://mermaid.live/edit#pako:eNp9U11vmzAU_SuWn7qIRHwmAU2VuvI0NR1qpj0M9uDgS0ACGxl7DYvy3-fgGKlVVXjB95xz7_HBPuOSU8AJLljV8teyJkKip5eCFQzpZ1CHoyB9jRaL3cPPp4dvi4UBUje_20siYTn0pAT09SDuUadbtV_-GEbm5fumU63mGHQYmaxBNiWiRBLLCvIfSkyVJRXNX2C3ViBrTm8kYPQDQ9moKcwayvw8G59VlzZV9ansu2obMqui_BleEWEUVYSVoxkuOW8P_PRpm8f9L1Q1LQxzIl5-twMyKAEdMDnYHFL_Td1MoKD3SqTe78ybxlw_bs7C_AVIa-hw6rXgKrexhWi5vNczrbPUnQqZZ8OfcePNoL7NyqC-dWjQ4C05mknvX-zgo2goTqRQ4OAOREeuS3y-diiw_s0dFDjRnxQqolpZ6PN10bKesN-cd1YpuDrWOKlIO-iV6vUxgLQhOuNurgodDIhHrpjESRRspiY4OeMTTtbBau1Fcei6cRDHoRc6eMSJt3ZXoR9t3DCO1m4Ubi4O_jdNdVfbref7az-IQtf3t_HWwURJvh9ZaT0BbSQXO3Mrpstx-Q-pbfHF)

## We need a standard

The weakness of this workflow is that:

**we need software-independent standards**
```
