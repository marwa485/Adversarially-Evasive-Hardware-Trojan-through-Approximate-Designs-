# Adversarially-Evasive-Hardware-Trojan-through-Approximate-Designs-

## Architecture

![Architecture of the Proposed Approach](HT.pdf)

## Abstract

The risk of hardware Trojans (HTs) being embedded into hardware designs has escalated significantly with the globalization of the economy and the increasing reliance on third-party services within contemporary integrated circuit (IC) supply chains. To counter this threat, a promising approach involves using Machine Learning (ML) architectures, which have demonstrated substantial effectiveness in detecting malicious circuits. However, in such a strategic domain, the arms race is unrelenting, and recent studies advocate leveraging ML vulnerability to adversarial noise to build evasive HTs. While these approaches highlight a potential vulnerability, they lack practicality since they require a high circuitry overhead for the evasive HT.

In this paper, we propose a new approach to generate evasive HTs under realistic assumptions with virtually no circuit overheads. To do so, we question the need for strict correctness of the HT circuit from the attacker’s perspective, which allows us to define a new approximate adversarial design space. Hence, we introduce a new gradient-free framework to generate evasive HTs by modifying the circuits with approximate gate replacement to produce evasive Trojans. The proposed approach uses a multi-objective evolutionary search algorithm to balance two critical objectives: approximation error and HT detection performance.

In contrast to previous work, which frequently considers white-box scenarios in which the attacker has complete access to the defender’s model, we investigate a more realistic black-box scenario in which the attacker is unaware of the defender’s detection model. This hypothesis is consistent with practical adversarial circumstances, allowing us to assess the long-term effectiveness of detection techniques under more restricted but realistic scenarios.

Our experiments show that our attack effectively creates overhead-free evasive Trojans, with a 91.6% decrease in detection accuracy while maintaining HT payload functionality with a 35% correctness. We believe the HT detection effort needs to systematically take into account the practical adversarial capabilities, and we extend the TrustHub benchmark to build TrustHub+, a dataset designed primarily for the analysis and evaluation of evasive HTs, ensuring comprehensive representation of these evasive HTs.
