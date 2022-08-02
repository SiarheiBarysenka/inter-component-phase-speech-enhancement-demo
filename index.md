This page contains listening examples of noisy and enhanced speech processed in the fully blind setup using algorithms proposed and/or evaluated in [[1]](#bibliography).

---

### Female Speech in Modulated Pink Noise (SNR = 5 dB)

| Clean  | Noisy |
| ------------- | ------------- |
| PESQ = **4.50**, STOI = **1.00**, PDev = **0.00**, NAseg = **∞ dB** | PESQ = **1.55**, STOI = **0.77**, PDev = **0.64**, NAseg = **0.00 dB** |
| <video src="https://user-images.githubusercontent.com/2571033/182360664-5ed7d437-ae16-4e18-b301-1d20926821f2.mp4" controls="controls" style="max-width: 400px;"></video> | <video src="https://user-images.githubusercontent.com/2571033/182360769-b216b222-a20b-408c-b30f-f1c6a236a584.mp4" controls="controls" style="max-width: 400px;"></video> |

#### Phase-Only Enhancement:

| Smooth Everywhere + Barysenka-Vorobiov-Mowlaee | Smooth Everywhere + Bartelt-Lohmann-Wirnitzer |
| ------------- | ------------- |
| PESQ = **1.80**, STOI = **0.78**, PDev = **0.53**, NAseg = **1.58 dB** | PESQ = **1.80**, STOI = **0.78**, PDev = **0.59**, NAseg = **1.66 dB** |
| <video src="https://user-images.githubusercontent.com/2571033/182363022-0bb9832a-c187-40bd-9ec6-8673d8156408.mp4" controls="controls" style="max-width: 400px;"></video> | <video src="https://user-images.githubusercontent.com/2571033/182363120-ca1d3e0c-b99e-48b3-8d2e-0e8e39c68911.mp4" controls="controls" style="max-width: 400px;"></video> |

| Binary Hypothesis + Barysenka-Vorobiov-Mowlaee *(proposed)* | Binary Hypothesis + Bartelt-Lohmann-Wirnitzer *(proposed)* |
| ------------- | ------------- |
| PESQ = **1.88**, STOI = **0.81**, PDev = **0.51**, NAseg = **1.55 dB** | PESQ = **1.82**, STOI = **0.81**, PDev = **0.53**, NAseg = **1.58 dB** |
| <video src="https://user-images.githubusercontent.com/2571033/182363436-41ec2b30-1fbe-41a6-86f8-3c1268727221.mp4" controls="controls" style="max-width: 400px;"></video> | <video src="https://user-images.githubusercontent.com/2571033/182363500-6b5f4690-7ec5-499e-b158-a826f0908523.mp4" controls="controls" style="max-width: 400px;"></video> |

#### Combined Magnitude & Phase Enhancement:

| MMSE-LSA + Unprocessed Phase | MMSE-LSA + Clean Phase |
| ------------- | ------------- |
| PESQ = **2.38**, STOI = **0.81**, NAseg = **10.03 dB** | PESQ = **2.62**, STOI = **0.85**, NAseg = **11.00 dB** |
| <video src="https://user-images.githubusercontent.com/2571033/182364253-e7ce7736-70ee-496a-a69a-5ebd405c696a.mp4" controls="controls" style="max-width: 400px;"></video> | <video src="https://user-images.githubusercontent.com/2571033/182368654-53cba9e9-5dd6-4172-8699-545339cee5e4.mp4" controls="controls" style="max-width: 400px;"></video> |

| MMSE-LSA + Smooth Everywhere + Barysenka-Vorobiov-Mowlaee | MMSE-LSA + Smooth Everywhere + Bartelt-Lohmann-Wirnitzer |
| ------------- | ------------- |
| PESQ = **2.61**, STOI = **0.81**, PDev = **0.41**, NAseg = **10.98 dB** | PESQ = **2.60**, STOI = **0.81**, PDev = **0.49**, NAseg = **11.11 dB** |
| <video src="https://user-images.githubusercontent.com/2571033/182363917-dfeb5633-603d-4d9a-8995-04b49dd9774f.mp4" controls="controls" style="max-width: 400px;"></video> | <video src="https://user-images.githubusercontent.com/2571033/182364020-e735b9e4-5623-4294-b6d8-490cd40c10ee.mp4" controls="controls" style="max-width: 400px;"></video> |

| MMSE-LSA + Binary Hypothesis + Barysenka-Vorobiov-Mowlaee *(proposed)* | MMSE-LSA + Binary Hypothesis + Bartelt-Lohmann-Wirnitzer *(proposed)* |
| ------------- | ------------- |
| PESQ = **2.66**, STOI = **0.82**, PDev = **0.40**, NAseg = **10.97 dB** | PESQ = **2.65**, STOI = **0.82**, PDev = **0.43**, NAseg = **11.07 dB** |
| <video src="https://user-images.githubusercontent.com/2571033/182364130-c1267a70-d3c3-4c3f-9347-a9accbed9122.mp4" controls="controls" style="max-width: 400px;"></video> | <video src="https://user-images.githubusercontent.com/2571033/182364083-68581f4c-e34f-41e5-b909-26fe8cf72034.mp4" controls="controls" style="max-width: 400px;"></video> |

---

### Bibliography

[1] S.Y. Barysenka, P. Mowlaee and V.I. Vorobiov, **“SNR-Based Inter-Component Phase Estimation Using Bi-Phase Prior Statistics for Single-Channel Speech Enhancement,”** *Submitted to IEEE/ACM Trans. Audio, Speech, and Language Process.*, 2022.
