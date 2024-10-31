# Shelf-Secure
Shelf Secure is a secure, hardware-based inventory management solution designed to track, monitor, and protect assets in real-time. Combining RFID and access control technologies, it enables efficient tracking, reduces loss, and enhances overall security, making inventory management seamless and secure for businesses.

This project showcases the design of a digital circuit-based inventory management system tailored for ACME Toy Company, which aims to transition its inventory tracking from software to a secure hardware solution to minimize cybersecurity risks. The design uses Logisim to create a highly modular, secure circuit that manages and adjusts stock levels based on month-by-month inputs.

## Key Features:
Month Decoder: A custom-built 4-to-16 decoder, assembled hierarchically from 2-to-4 and 3-to-8 decoders, translates month inputs (0-11) into signals for January, December, and other months based on specific stock behaviors, including increased demand at the year's start, minimal demand during odd-numbered months, and end-of-year adjustments.

Stock Calculator and Error Handling: By employing OR gates and a unique error output, the system manages inventory changes and error signaling for invalid months (values > 11). The design integrates secure, error-free logic flow to prevent unauthorized or unintended alterations to stock.

Memory and Stock Adjustment: The Part B circuit features a custom 4-bit adder/subtractor and memory (D flip-flops) to track stock levels accurately across 0-15 pallets. Inputs for stock increases/decreases align with monthly demands, ensuring seamless updates with manual clock control for stability. The design enhances circuit resilience by using subcircuits and modular elements to improve fault isolation.

This project blends fundamental digital logic with practical applications in secure stock management, showcasing the potential of hardware-based solutions in enhancing cybersecurity within inventory control. The complete circuit, including screenshots and detailed documentation, is available in this GitHub repository.






