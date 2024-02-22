<detail>
 <summary> TASK 2 </summary>


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
 
 
</head>
<body>
    <h1>RISC-V Instruction Types</h1>
    <p>RISC-V is an open-source instruction set architecture (ISA) with various instruction formats. Here are the primary types:</p>
    <ul>
        <li><strong>R-Type Instructions (Register-Register Operations):</strong> Operations between two registers (e.g., <code>add</code>, <code>sub</code>).</li>
        <li><strong>I-Type Instructions (Immediate and Load Operations):</strong> Work with immediate values and memory loads (e.g., <code>addi</code>, <code>lw</code>).</li>
        <li><strong>S-Type Instructions (Store Operations):</strong> Store data from a register into memory (e.g., <code>sw</code>).</li>
        <li><strong>B-Type Instructions (Conditional Branch Operations):</strong> Perform conditional jumps (e.g., <code>beq</code>, <code>bne</code>).</li>
        <li><strong>U-Type Instructions (Long Immediates):</strong> Handle long immediate values (e.g., <code>lui</code>).</li>
        <li><strong>M-Type Instructions (Integer Multiplication and Division):</strong> Handle integer arithmetic (e.g., <code>mul</code>, <code>div</code>).</li>
        <li><strong>A-Type Instructions (Atomic Operations):</strong> Provide atomic memory operations (e.g., <code>lr.w</code>, <code>sc.w</code>).</li>
        <li><strong>F-Type Instructions (Single-Precision Floating Point):</strong> Deal with single-precision floating-point arithmetic (e.g., <code>fadd.s</code>).</li>
        <li><strong>D-Type Instructions (Double-Precision Floating Point):</strong> Handle double-precision floating-point arithmetic (e.g., <code>fadd.d</code>).</li>
        <li><strong>Q-Type Instructions (Quad-Precision Floating Point):</strong> Work with quad-precision floating-point numbers.</li>
        <li><strong>C-Type Instructions (Compressed Instructions):</strong> 16-bit instructions for code density (e.g., <code>c.addi4spn</code>, <code>c.lw</code>).</li>
<h2><b>Instruction code format </b></h2>
	<br>![123](https://github.com/rajath55555/rajathkumar/assets/119932039/289e8089-715d-4618-9159-6165f70e44ee)


</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>RISC-V Overview</title>
</head>
<body>
    <h1>RISC-V Architecture and Registers</h1>
    <p>RISC-V is an open standard instruction set architecture (ISA) based on reduced instruction set computer (RISC) principles. Unlike most other ISA designs, RISC-V is provided under royalty-free open-source licenses. [^1^][1] [^2^][2]</p>
    <p>RISC-V architecture defines a set of registers that are used for various purposes. The register file in RISC-V consists of 32 general-purpose registers (integer registers), denoted as x0 to x31. The x0 register is hardwired to zero and cannot be modified. Here's a brief overview of the RISC-V registers:</p>
    <h2>General-Purpose Registers (x0 to x31)</h2>
    <ul>
        <li>x0 is hardwired to zero.</li>
        <li>x1 to x31 are general-purpose registers used for data manipulation and storage.</li>
    </ul>
    <h2>Special Registers</h2>
    <ul>
        <li>Program Counter (pc): Keeps track of the address of the current instruction being executed.</li>
        <li>Link Register (lr or x1): Used to store the return address for function calls.</li>
        <li>Stack Pointer (sp or x2): Points to the top of the stack.</li>
        <li>Frame Pointer (fp or x8): Used as a reference point for accessing local variables and parameters in functions.</li>
        <li>Zero Register (zero or x0): Hardwired to zero and cannot be modified. Often used for operations that require a constant zero value.</li>
    </ul>
    <h2>Saved Registers</h2>
    <p>Registers x8 to x15 are often designated as "saved" registers, which means they must be preserved across function calls.</p>
    <h2>Temporary Registers</h2>
    <p>Registers x5 to x7 are designated as temporaries and can be freely used within a function without the need to preserve their values across function calls.</p>
    <h2>Argument Registers</h2>
    <p>Registers x10 to x17 are typically used for passing arguments to functions.</p>
    <h2>Return Value Registers</h2>
    <p>Registers x10 and x11 are commonly used to store the return values of functions.</p>
</body>
</html>
