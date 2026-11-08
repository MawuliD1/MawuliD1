# Selected Projects and Technical Work

This document presents research and engineering work drawn from my academic and professional experience. Reported numerical results are retained in their stated experimental or simulation context. Code, data and co-authored materials will be linked only where public release is permitted.

## 1. STAR-RIS-assisted integrated sensing and covert communication

**Publication title:** *STAR-RIS-Assisted Integrated Sensing and Covert Communication via Ambiguity-Domain Signal Hiding and Temporal Phase Randomization.*

- Co-engineered a STAR-RIS framework concealing covert data in radar delay-Doppler ambiguity sidelobes, maintaining a reported 1.77 dB margin below the radar peak sidelobe level, with PSL of -13.47 dB.
- Formulated per-pulse temporal phase randomisation to induce Doppler-estimability asymmetry against energy, coherent and optimal likelihood-ratio-test wardens. The reported minimum detection error probability was 0.919, meeting the stated threshold of 0.90.
- Developed a Riemannian-manifold alternating optimisation framework balancing Cramér-Rao-bound sensing with covert throughput. The reported covert rate was 8.13 bits/symbol, with monotonic convergence in three iterations.
- **Conference:** Presented as a co-authored paper at IEEE ICAST 2026, Accra, Ghana.

## 2. Lightweight on-device CNN for audio deepfake detection in mobile banking

**Publication title:** *A Lightweight On-Device CNN for Real-Time Audio Deepfake Detection in Mobile Banking Applications.*

- Developed a 547,000-parameter CNN with a 2.10 MB float32 model size and a 0.60 MB INT8 model size.
- Reported CPU inference latency of 4.962 ms.
- Evaluated using ASVspoof 2019/2021 LA datasets under raw G.711 codec and additive white Gaussian noise (AWGN) conditions.
- Reported a clean equal error rate (EER) of 9.84%.
- Under 20 dB noise, reported 14.80% EER, compared with 16.41% for a model eight times larger.
- Conducted frequency-band ablation, identifying the 0–2 kHz bands as an important concentration of discriminative features.
- **Conference:** Presented as a co-authored paper at IEEE ICAST 2026, Accra, Ghana.

## 3. Resilient low-power LoRa mesh network for remote forest conservation

**Publication title:** *Design and Evaluation of a Resilient Low-Power LoRa Mesh Network for Remote Forest Conservation.*

- Modelled 868 MHz foliage loss and knife-edge diffraction over distances up to 1,000 m.
- Analysed single-hop link collapse within 265 m under the studied terrain-obstruction conditions.
- Built a stateless Layer-2 forwarding engine in ns-3 with sequence deduplication and 150–400 ms randomised backoff, mapped to Semtech AN1200.13 Time-on-Air models.
- Reported 100% packet delivery ratio across an 800 m obstructed corridor using five nodes at 200 m spacing, compared with 0% for the direct star LoRaWAN baseline in the evaluated scenario.
- **Conference:** Presented as a co-authored paper at IEEE ICAST 2026, Accra, Ghana.

## 4. Machine-learning-based DDoS detection and mitigation in SDN-enabled 5G networks

Undergraduate thesis research investigating DDoS detection and mitigation in a simulated SDN-enabled 5G mobile network with multiple controllers.

- Led a team of three students evaluating deep neural network (DNN), long short-term memory (LSTM) and support vector machine (SVM) models.
- Integrated optimised machine-learning models into a multiple-controller SDN architecture.
- Reported model accuracies of 99.48% for DNN, 99.57% for LSTM and 98.89% for SVM following hyperparameter tuning.
- Evaluated controller scalability, mitigation latency and throughput preservation under attack traffic in a simulated environment.
- Conducted comparative analysis of model performance for DDoS detection and mitigation.
- **Tools and methods:** Mininet, Ryu, OpenFlow, Python and machine-learning methods.

These are reported experimental results from a simulated research environment, not claims of deployment or verified performance in a live commercial 5G network. A public technical repository should document dataset provenance, feature definitions, data splitting, class balance, leakage controls, evaluation metrics and reproducibility.

## 5. Deep-learning-based downlink precoding and CSI compression for massive MIMO

Research collaboration with Ing. K. A. P. Agyekum on deep-learning-based downlink precoding for multi-antenna users in massive MIMO systems.

- Developed a Transformer-based precoding scheme aimed at improving spectral efficiency and reducing CSI overhead.
- Designed a self-attention model for efficient CSI compression.
- Validated the approach through simulations.

## 6. Crypto-ransomware detection and mitigation using machine learning

Applied machine-learning algorithms to research the detection and mitigation of cryptographic ransomware attacks. Public documentation should identify the evaluation environment, dataset provenance, labelling assumptions and limitations. Malware samples, credentials and unsafe executable content must not be published.

## 7. AI-powered surveillance threat assessment and autonomous security alerts

Researched a multi-modal security monitoring approach combining YOLO-based object detection with C3D/I3D action recognition. The work included automated alert notifications for threat-response support. Public demonstrations must respect privacy, consent and dataset licences. Automated classifications should not be presented as definitive evidence of intent or wrongdoing.

## 8. Non-Orthogonal Multiple Access (NOMA)

Explored NOMA techniques intended to improve spectrum efficiency and data throughput in next-generation wireless communication.

## 9. 5 GHz patch antenna design and simulation

Designed and simulated 5 GHz patch antennas using Ansys HFSS, evaluating radiation patterns, S11 and voltage standing wave ratio (VSWR) against RF transceiver design requirements.

## 10. Intelligent IoT energy conservation and automated irrigation

Implemented a smart metering system for energy-conservation monitoring and developed a sensor-actuator irrigation framework to optimise agricultural water use.

## 11. Industrial electrical engineering exposure

Practical engineering experience includes MV/LV inspections, isolation, testing, restoration and preventive maintenance support for motors, motor control centres (MCCs), UPS units and substation equipment. Work exposure includes 6 kV and 380/400 V switchgear, PLC-controlled motors, electrical drawings, AC/DC schematics and operational data analysis.

No confidential plant drawings, switching schedules, control configurations, operational records or proprietary information are included in this public profile.

## Project publication and confidentiality checklist

Before publishing any project repository:
1. Confirm project title, scope, status and individual contribution.
2. Obtain required co-author, supervisor, employer and institutional permissions.
3. Check licences and redistribution rights for code, datasets, figures and documents.
4. Remove credentials, tokens, personal data and sensitive operational information.
5. Explain methods, evaluation, limitations and reproducibility requirements.
6. Include appropriate references and acknowledgements.

Do not publish confidential Tema Oil Refinery information, internal drawings, control configurations, operational records, proprietary Cyber Secured Africa materials or restricted institutional datasets.
