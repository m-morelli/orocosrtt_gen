# orocosrtt_gen - Model transformation from Synchronous models to the Orocos-RTT middleware

orocosrtt_gen contains model transformations to generate a SW implementation of robot control applications that preserves the execution semantics of functional model (Synchronous-Reactive as, e.g., in Simulink) and, in turn, the system properties formally verified during the design phase. The SW architecture model is defined in SysML/MARTE using the mapping profile in [cypbd_mapping](https://github.com/m-morelli/cypbd_mapping). The target of the generation process is the Orocos-RTT robotic middleware.

*orocosrtt_gen is in the early phases of development. Only the model-to-model transformations that generate a model of BSW (based on Orocos-RTT) from a model of the SW architecture are included in the repository. The model-to-code transformation templates that produce the real C++ code are still in progress.*

# Note on Licensing

orocosrtt_gen is released under the terms of the permissive, industry-friendly 3-Clause BSD License.
