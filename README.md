- 👋 Hi, I’m @Hadi8133
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Hadi8133/Hadi8133 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->XPMArgumentSignature
  *inFiles = [XPMArgumentSignature argumentSignatureWithFormat:@"[-f --input-files]={1,5}"],
  *outputFiles = [XPMArgumentSignature argumentSignatureWithFormat:@"[-o --output-files]={1,5}"];

// on the command line:

foo -ofv ouput1 output2 output3 -- input1 input2 input3 input4 # use the double-dash to separate
foo -of ouput1 output2 output3 -v input1 input2 input3 input4 # use the verbose flag to separate
