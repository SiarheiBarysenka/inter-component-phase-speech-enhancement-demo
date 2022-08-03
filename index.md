This page contains listening examples of noisy and enhanced speech processed in the fully blind setup using algorithms proposed and/or evaluated in [[1]](#bibliography).

---

## Female Speech in Modulated Pink Noise (SNR = 5 dB)

| Clean  | Noisy |
| :--- | :--- |
| PESQ = **4.50**, STOI = **1.00**, PDev = **0.00**, NA<sub>seg</sub> = **∞ dB** | PESQ = **1.55**, STOI = **0.77**, PDev = **0.64**, NA<sub>seg</sub> = **0.00 dB** |
| <video src="https://user-images.githubusercontent.com/2571033/182360664-5ed7d437-ae16-4e18-b301-1d20926821f2.mp4" controls="controls" style="max-width: 400px;"></video> | <video src="https://user-images.githubusercontent.com/2571033/182360769-b216b222-a20b-408c-b30f-f1c6a236a584.mp4" controls="controls" style="max-width: 400px;"></video> |

&nbsp;
&nbsp;
### Phase-Only Enhancement

| Smooth Everywhere + Barysenka-Vorobiov-Mowlaee | Smooth Everywhere + Bartelt-Lohmann-Wirnitzer |
| :--- | :--- |
| PESQ = **1.80**, STOI = **0.78**, PDev = **0.53**, NA<sub>seg</sub> = **1.58 dB** | PESQ = **1.80**, STOI = **0.78**, PDev = **0.59**, NA<sub>seg</sub> = **1.66 dB** |
| <video src="https://user-images.githubusercontent.com/2571033/182363022-0bb9832a-c187-40bd-9ec6-8673d8156408.mp4" controls="controls" style="max-width: 400px;"></video> | <video src="https://user-images.githubusercontent.com/2571033/182363120-ca1d3e0c-b99e-48b3-8d2e-0e8e39c68911.mp4" controls="controls" style="max-width: 400px;"></video> |

&nbsp;

| Binary Hypothesis + Barysenka-Vorobiov-Mowlaee *(proposed)* | Binary Hypothesis + Bartelt-Lohmann-Wirnitzer *(proposed)* |
| :--- | :--- |
| PESQ = **1.88**, STOI = **0.81**, PDev = **0.51**, NA<sub>seg</sub> = **1.55 dB** | PESQ = **1.82**, STOI = **0.81**, PDev = **0.53**, NA<sub>seg</sub> = **1.58 dB** |
| <video src="https://user-images.githubusercontent.com/2571033/182363436-41ec2b30-1fbe-41a6-86f8-3c1268727221.mp4" controls="controls" style="max-width: 400px;"></video> | <video src="https://user-images.githubusercontent.com/2571033/182363500-6b5f4690-7ec5-499e-b158-a826f0908523.mp4" controls="controls" style="max-width: 400px;"></video> |

&nbsp;
&nbsp;
### Combined Magnitude & Phase Enhancement

| MMSE-LSA + Unprocessed Phase *(lower bound)* | MMSE-LSA + Clean Phase *(upper bound)* |
| :--- | :--- |
| PESQ = **2.38**, STOI = **0.81**, NA<sub>seg</sub> = **10.03 dB** | PESQ = **2.62**, STOI = **0.85**, NA<sub>seg</sub> = **11.00 dB** |
| <video src="https://user-images.githubusercontent.com/2571033/182364253-e7ce7736-70ee-496a-a69a-5ebd405c696a.mp4" controls="controls" style="max-width: 400px;"></video> | <video src="https://user-images.githubusercontent.com/2571033/182368654-53cba9e9-5dd6-4172-8699-545339cee5e4.mp4" controls="controls" style="max-width: 400px;"></video> |

&nbsp;

| MMSE-LSA + Smooth Everywhere + Barysenka-Vorobiov-Mowlaee | MMSE-LSA + Smooth Everywhere + Bartelt-Lohmann-Wirnitzer |
| :--- | :--- |
| PESQ = **2.61**, STOI = **0.81**, PDev = **0.41**, NA<sub>seg</sub> = **10.98 dB** | PESQ = **2.60**, STOI = **0.81**, PDev = **0.49**, NA<sub>seg</sub> = **11.11 dB** |
| <video src="https://user-images.githubusercontent.com/2571033/182363917-dfeb5633-603d-4d9a-8995-04b49dd9774f.mp4" controls="controls" style="max-width: 400px;"></video> | <video src="https://user-images.githubusercontent.com/2571033/182364020-e735b9e4-5623-4294-b6d8-490cd40c10ee.mp4" controls="controls" style="max-width: 400px;"></video> |

&nbsp;

| MMSE-LSA + Binary Hypothesis + Barysenka-Vorobiov-Mowlaee *(proposed)* | MMSE-LSA + Binary Hypothesis + Bartelt-Lohmann-Wirnitzer *(proposed)* |
| :--- | :--- |
| PESQ = **2.66**, STOI = **0.82**, PDev = **0.40**, NA<sub>seg</sub> = **10.97 dB** | PESQ = **2.65**, STOI = **0.82**, PDev = **0.43**, NA<sub>seg</sub> = **11.07 dB** |
| <video src="https://user-images.githubusercontent.com/2571033/182364130-c1267a70-d3c3-4c3f-9347-a9accbed9122.mp4" controls="controls" style="max-width: 400px;"></video> | <video src="https://user-images.githubusercontent.com/2571033/182364083-68581f4c-e34f-41e5-b909-26fe8cf72034.mp4" controls="controls" style="max-width: 400px;"></video> |

---

## Male Speech in Babble Noise (SNR = 3 dB)

| Clean  | Noisy |
| :--- | :--- |
| PESQ = **4.50**, STOI = **1.00**, PDev = **0.00**, NA<sub>seg</sub> = **∞ dB** | PESQ = **1.66**, STOI = **0.81**, PDev = **0.62**, NA<sub>seg</sub> = **0.00 dB** |
| <video src="https://user-images.githubusercontent.com/2571033/182592742-6894e76d-41f4-456f-9479-9247d8d13816.mp4" controls="controls" style="max-width: 400px;"></video> | <video src="https://user-images.githubusercontent.com/2571033/182592803-e054bd20-2502-4b4f-ac79-5f873ddeef27.mp4" controls="controls" style="max-width: 400px;"></video> |

&nbsp;
&nbsp;
### Phase-Only Enhancement

| Smooth Everywhere + Barysenka-Vorobiov-Mowlaee | Smooth Everywhere + Bartelt-Lohmann-Wirnitzer |
| :--- | :--- |
| PESQ = **1.81**, STOI = **0.77**, PDev = **0.67**, NA<sub>seg</sub> = **2.80 dB** | PESQ = **1.74**, STOI = **0.75**, PDev = **0.79**, NA<sub>seg</sub> = **3.11 dB** |
| <video src="https://user-images.githubusercontent.com/2571033/182593017-89e4ec9e-f67a-4a13-8a77-51d690652637.mp4" controls="controls" style="max-width: 400px;"></video> | <video src="https://user-images.githubusercontent.com/2571033/182593079-a1307dbd-e85f-467c-9f7f-e7707d7ea7ef.mp4" controls="controls" style="max-width: 400px;"></video> |

&nbsp;

| Binary Hypothesis + Barysenka-Vorobiov-Mowlaee *(proposed)* | Binary Hypothesis + Bartelt-Lohmann-Wirnitzer *(proposed)* |
| :--- | :--- |
| PESQ = **1.88**, STOI = **0.81**, PDev = **0.57**, NA<sub>seg</sub> = **2.57 dB** | PESQ = **1.75**, STOI = **0.80**, PDev = **0.58**, NA<sub>seg</sub> = **2.73 dB** |
| <video src="https://user-images.githubusercontent.com/2571033/182593389-665f5c30-11c0-478b-b53a-b8b2f8b8c306.mp4" controls="controls" style="max-width: 400px;"></video> | <video src="https://user-images.githubusercontent.com/2571033/182593444-339f4c12-d30d-4e19-ab9f-ee00908e8fc5.mp4" controls="controls" style="max-width: 400px;"></video> |

&nbsp;
&nbsp;
### Combined Magnitude & Phase Enhancement

| MMSE-LSA + Unprocessed Phase *(lower bound)* | MMSE-LSA + Clean Phase *(upper bound)* |
| :--- | :--- |
| PESQ = **1.90**, STOI = **0.82**, NA<sub>seg</sub> = **9.15 dB** | PESQ = **2.29**, STOI = **0.87**, NA<sub>seg</sub> = **10.65 dB** |
| <video src="https://user-images.githubusercontent.com/2571033/182593665-fa0d8618-cebe-46d9-b74e-f23f31806142.mp4" controls="controls" style="max-width: 400px;"></video> | <video src="https://user-images.githubusercontent.com/2571033/182593711-1688e1a5-cc20-461a-813d-30f8fdfbd50d.mp4" controls="controls" style="max-width: 400px;"></video> |

&nbsp;

| MMSE-LSA + Smooth Everywhere + Barysenka-Vorobiov-Mowlaee | MMSE-LSA + Smooth Everywhere + Bartelt-Lohmann-Wirnitzer |
| :--- | :--- |
| PESQ = **2.01**, STOI = **0.80**, PDev = **0.65**, NA<sub>seg</sub> = **11.08 dB** | PESQ = **1.92**, STOI = **0.78**, PDev = **0.64**, NA<sub>seg</sub> = **12.01 dB** |
| <video src="https://user-images.githubusercontent.com/2571033/182593918-173ad31d-bd34-4ef3-9bda-a3f1f5003b40.mp4" controls="controls" style="max-width: 400px;"></video> | <video src="https://user-images.githubusercontent.com/2571033/182594146-de25b7cd-1891-46a0-9bcd-a64e965950ab.mp4" controls="controls" style="max-width: 400px;"></video> |

&nbsp;

| MMSE-LSA + Binary Hypothesis + Barysenka-Vorobiov-Mowlaee *(proposed)* | MMSE-LSA + Binary Hypothesis + Bartelt-Lohmann-Wirnitzer *(proposed)* |
| :--- | :--- |
| PESQ = **1.97**, STOI = **0.82**, PDev = **0.55**, NA<sub>seg</sub> = **10.78 dB** | PESQ = **1.93**, STOI = **0.80**, PDev = **0.57**, NA<sub>seg</sub> = **11.14 dB** |
| <video src="https://user-images.githubusercontent.com/2571033/182594424-2b682a16-5176-4161-ad76-3b6d90fe6053.mp4" controls="controls" style="max-width: 400px;"></video> | <video src="https://user-images.githubusercontent.com/2571033/182594468-1d533587-349d-4e0a-bf47-7576879f4e4b.mp4" controls="controls" style="max-width: 400px;"></video> |

---

## Bibliography

[1] S.Y. Barysenka, P. Mowlaee and V.I. Vorobiov, **“SNR-Based Inter-Component Phase Estimation Using Bi-Phase Prior Statistics for Single-Channel Speech Enhancement,”** *Submitted to IEEE/ACM Transactions on Audio, Speech and Language Processing*, 2022.
