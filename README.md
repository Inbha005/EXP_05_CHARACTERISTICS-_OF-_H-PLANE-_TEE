# exp_5_characteriztion_of_h_plane

# Experiment 5 —  Characterization of H-Plane Tee

---

## Aim

To study the characteristics of an H–plane tee (shunt tee) and to determine the power–division ratio between its collinear arms and the isolation between them.
## Apparatus Used

Klystron power supply, klystron mount with tube, isolator, variable attenuator, frequency meter, slotted line section, E-plane tee, detector mount / crystal detector, matched terminations, VSWR meter, waveguide stands.

## Experimental Setup

<img width="933" height="296" alt="Screenshot 2026-09-22 184359" src="https://github.com/user-attachments/assets/d910d18a-cc66-44f7-8c5e-8a887383cacf" />


---

## Theory

An H–plane tee is a waveguide junction in which the axis of the side arm is parallel to the plane of the magnetic (H) field of the main waveguide, obtained by cutting a rectangular slot along the broad wall of the guide. It is a shunt junction: when power is fed into the side arm (port 3), it splits equally between the two collinear arms (ports 1 and 2) and emerges in phase at both. Conversely, when equal and in–phase signals are fed into the two collinear arms, they add constructively at the side arm; when fed with equal but out–of–phase signals, they cancel at the side arm. Because of the equal, in–phase power split it provides, the H–plane tee is commonly used as a power divider/combiner.

CIRCUIT / PORT DIAGRAM

<img width="667" height="442" alt="Screenshot 2026-09-22 184813" src="https://github.com/user-attachments/assets/76c591fd-f344-4133-bf27-0997a17770bc" />

---

## Procedure

1. The bench is set up with the H–plane tee connected as the device under test and the klystron output stabilised.
2. Power is fed into the H–arm (port 3); port 2 is terminated in a matched load and the detector is connected to port 1, and the output reading is noted.
3. The detector and matched load are then interchanged between ports 1 and 2, and the output at port 2 is noted with port 1 terminated.
4. To find the isolation between the two collinear arms, power is fed into port 1, port 3 is terminated in a matched load, and the leakage at port 2 is measured. 5. All readings are recorded in dB.

PROCEDURE FLOWCHART

<img width="1007" height="530" alt="Screenshot 2026-09-22 184949" src="https://github.com/user-attachments/assets/0bb80147-7641-4e23-bfae-7c7306fe05f4" />


---

## Observation

TABULATION

<img width="1063" height="140" alt="Screenshot 2026-09-22 185027" src="https://github.com/user-attachments/assets/3681a816-4843-47d9-8709-f4950742d5ef" />
<img width="1063" height="92" alt="Screenshot 2026-09-22 185052" src="https://github.com/user-attachments/assets/3dcd6bee-afba-4d81-8c1b-7f6db069f262" />

FORMULA

1. Power division ratio (Port 3 → Port 1, Port 2) = Pin – Pout = 10 log10 (Pin / Pout) dB (ideally ≈ 3 dB at each arm)
2. Isolation between collinear arms = 10 log10 (P1 / P2) dB

MODEL GRAPH AND ACTUAL GRAPH

<img width="1027" height="390" alt="Screenshot 2026-09-22 185158" src="https://github.com/user-attachments/assets/7cfdad95-a7b6-440b-a078-1a376db2beac" />

CALCULATION

1. Power at Port 1 (from Port 3) = 0.0 – (–3.3) = 3.3 dB down.
2. Power at Port 2 (from Port 3) = 0.0 – (–3.6) = 3.6 dB down.
3. Since both arms are within about 0.3 dB of each other and close to the ideal 3 dB point, the H–arm divides power essentially equally between the two collinear arms.
4. Isolation (Port 1 → Port 2, with Port 3 matched) = 0.0 – (–25.0) = 25.0 dB.
---

## Precautions

1. Unused ports must always be terminated in matched loads.
2. Flange connections should be tight and properly aligned to avoid reflections.
3. The klystron source should be allowed to stabilise before readings are taken.
4. Do not look directly into the open waveguide.

RESULT 

The power–division ratio between the collinear arms of the given H–plane tee was found to be 3.3 dB and 3.6 dB (nearly equal, in phase), and the isolation between the collinear arms was found to be 25.0 dB, confirming the equal in–phase power split expected of an H–plane (shunt) junction.
