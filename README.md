# QSPICE-library

Text files for QSPICE libraries.

QSPICE supports existing LTSPICE models as long as they include `.model` statements. There are two primary methods for using these models:

---

## Method 1: Using Text Files with Listed Models

This method involves creating a text file that contains multiple `.model` statements. You can then select the desired model within the QSPICE schematic editor.

See [Standard.bjt](https://ltwiki.org/index.php?title=Standard.bjt) for an example on what the text file looks like.

Use the text files from this repository to follow the tutorial images below:

<img width="690" height="371" alt="Method 1 - Step 1" src="https://github.com/user-attachments/assets/e2eb4974-4722-4228-8012-e525e6d3c0a6" />
<img width="690" height="353" alt="Method 1 - Step 2" src="https://github.com/user-attachments/assets/1d6f828c-facd-4574-957c-a8d3643d07e8" />

---

## Method 2 (better method): Importing Models and Creating Symbols

This method involves importing a `.model` statement directly into the QSPICE schematic and generating a symbol for it. These symbols (.qsym files) can be selected from the Symbol Browser in QSPICE.

Use the .qsym files from this repository to follow the tutorial images below:

<img width="690" height="369" alt="Method 2 - Step 1" src="https://github.com/user-attachments/assets/74c567c9-137a-405e-a2f0-184c0e61e667" />
<img width="690" height="360" alt="Method 2 - Step 2" src="https://github.com/user-attachments/assets/62fafa63-2d75-491e-a476-e0d1b41a29c4" />

---

## Notes on Symbol Selection

There are two symbol usage styles in QSPICE:

- **.model embedded method**:  
  - One device per symbol  
  - Drag symbol into schematic and use directly

- **Selection guide method**:  
  - Multiple devices per symbol  
  - Right-click on symbol to choose model from selection guide  
  - Only supported for certain standard QSPICE devices

In the selection guide method, the symbol file (.qsym) does not contain the `.model` directly. Instead, it references a library file that includes multiple `.model` definitions.

---

## Additional Resources

- [SPICE Model Links](https://ltwiki.org/index.php?title=SPICE_Model_Links)  
- [QSPICE Forum Discussion](https://forum.qorvo.com/t/adding-model-files-to-qspice/14963/13)  
- [Standard.bjt Reference](https://ltwiki.org/index.php?title=Standard.bjt)

You can also find additional models across various GitHub repositories.
