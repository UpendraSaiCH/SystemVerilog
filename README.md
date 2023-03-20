# SystemVerilog
Implementation of layered test bench using SystemVerilog/Verilog

A layered testbench is a type of testbench architecture that is used in the verification of digital designs. It involves breaking down the testbench into multiple layers, each of which performs a specific function or checks a specific aspect of the design. The layers are typically arranged in a hierarchical manner, with the lower-level layers providing the foundation for the higher-level layers.

The different layers in a layered testbench can be categorized into three main types: stimulus, analysis, and scoreboarding. The stimulus layers generate input stimuli to simulate the behavior of the design being tested. The analysis layers capture the output responses from the design and verify that they meet the expected behavior. The scoreboarding layers compare the expected behavior with the actual behavior and report any discrepancies.

By breaking down the testbench into layers, the overall complexity of the verification process is reduced, making it easier to manage and debug. Each layer can be developed and verified independently, allowing for faster and more efficient testing. Additionally, the layered testbench approach enables more thorough testing, as each layer can be designed to test specific functionality or aspects of the design.

In summary, a layered testbench is a powerful verification technique that can help ensure the quality and functionality of digital designs. By dividing the testbench into layers, it is possible to manage the complexity of the verification process and perform more thorough testing.
