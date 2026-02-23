### **ReAct (Reason + Act) Pattern:** 

### **Flow**: 
- LLM receives question/task and **reasons** - "Do I have enough information to answer?"
- If not, LLM selects a tool
- **Act:** tool is called
- LLM observes the output of the tool
- LLM reasons: "Do I have everything I need for the correct output?"
- Loop until correct answer

### Reason -> Act -> Observe -> Reason -> Act or Answer ...