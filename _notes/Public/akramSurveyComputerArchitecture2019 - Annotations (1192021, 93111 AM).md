* Mdnotes File Name: [[akramSurveyComputerArchitecture2019]]

# Annotations(2021-11-08)
“Fidelity of simulation should be a serious concern, considering the reliance of major design decisions on simulation results. First, simulator developers have to make sure that simulators are functionally correct, if they are simulating a target’s functionality. Second, the performance statistics should indicate the target’s actual performance. Unfortunately, simulators are not always accurate and can exhibit various errors. Potentially, there can be three different types of errors in simulators [137]: Modeling errors, specification errors and abstraction errors.” (Akram and Sawalha, 2019, p. 78132)
(Akram and Sawalha, 2019, p. 78132) understanding different types of simulation errors
“Validating simulators usually incorporates modeling a real hardware and comparing the simulators results to those of the real hardware, then calculating the experimental error. If the experimental error is high, then first the types and sources of errors should be identified.” (Akram and Sawalha, 2019, p. 78133)
“A recent study [140], which calibrates MARSSx86 simulator for a particular target heterogeneous processor, concludes that an unvalidated/uncalibrated simulator can lead to considerable differences between simulation results and real architecture performance statistics.” (Akram and Sawalha, 2019, p. 78133)
“ughes et al. [42] argue that validating simulators can be impractical for research and many unvalidated simulators can prove useful and valuable in studying architectural phenomenon and relative performance. It can be a tedious job to validate a simulator due to: (1) the lack of certain details about modern processors where it becomes almost impossible to implement those systems precisely in simulators; (2) implementing some details of a modern processor, even when known, can be time consuming and can result in a slower simulation time; (3) modeling a target system that is just a a research idea, thus it is hard to validate. In such cases, it becomes impossible to validate simulators [33].” (Akram and Sawalha, 2019, p. 78133)
“Mostly, computer architects compare the results of their simulators with the performance behavior of benchmarks on the real machine that is being simulated. Sometimes, they also rely on published results for a particular hardware instead of running experiments on the real system. Desikan et al. [19] tried to validate SimpleScalar’s out-of-order model against Alpha 21264 processor model. The mean experimental error in microbenchmark simulation was reduced from 19.5% for sim-outorder, to 2% after validating sim-outorder for an Alpha processor (Sim-alpha).” (Akram and Sawalha, 2019, p. 78133)
“Perez et al. [21] compared performance estimation of various modules of MicroLib simulation environment with SimpleScalar to validate them. Walker et al. [144] proposed a new method to find sources of inaccuracies in simulators and validate them using clustering, correlation analysis and regression. Our previous work [148] compared the experimental error of few computer architecture simulators to an Intel’s Core-i7 microarchitecture.” (Akram and Sawalha, 2019, p. 78133)
“Gutierrez et al. [22] and Butko et al. [141] evaluated gem5’s accuracy to model actual processors based on ARM ISA (Cortex A15 and A9 microarchitectures). Gutierrez et al.’s experiments showed an average inaccuracy of 13% for SPEC CPU2006 benchmarks [22]. Butko et al. [141] studied gem5’s accuracy for multicore embedded target’s simulation. Tanimoto et al. [150] also pointed some of the issues with the out-of-order implementation of gem5. Walker et al. validated gem5 against two ARM microarchitectures [144]. The inaccuracy varied from 1.39% to 17.94% based on their experiments. Akram and Sawalha calculated the experimental error for gem5 with x86 ISA and pointed out some sources of inaccuracy [148]. However, there is no full validation effort for x86 ISA.” (Akram and Sawalha, 2019, p. 78134)
“Multi2Sim’s validation for GPUs has been done by Ubal et al. [142]. They used AMD Radeon 5870 as a target GPU model and AMD OpenCL SDK [152] applications for benchmarking. The results verified the functional correctness in addition to measuring the average percentage error in execution time (5% to 30%). To the best of our knowledge, there are no validation efforts for x86 CPUs for this simulator.” (Akram and Sawalha, 2019, p. 78134)
“ZSim’s validation [143] using an Intel Westmere core showed an error of 10% on average. Average absolute error for multi-threaded workloads is 11.2%. Different microbenchmarks, single threaded (SPECCPU2006) and multi threaded (PARSEC, SPLASH2) benchmarks were used for the validation effort. The validation study shows that” (Akram and Sawalha, 2019, p. 78134)
“Thus, there is a need for new methods to validate the relative accuracy of simulators. Similarly, there is a need to validate simulators for multicore processor simulation, as multicore simulation inaccuracies for simulators that were validated for single core processors show high error rates for multicore experiments.” (Akram and Sawalha, 2019, p. 78141)

