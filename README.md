# Per-Prompt Adaptive Parameter and Resource Allocation

## Scale is the Name of the Game: 
- Need to cut the power-usage of large models by a factor of 1000
- Not every prompt needs the same treatment
## What:
- Fine-grain selection of parameters based on the difficulty of the prompt
- Allocate resources to prompt based off parameters/cost/system state
- Adaptive tradeoff navigation at multiple levels (# of experts, # of agents, “thinking time”)
## Roadmap:
- Variable scaling of number of experts based off prompt
- Integrating a allocation system per-prompt
- Semantic Caching of parameters based on usage patterns; cache-aware routing
- Prompt and Agent based feedback to the routing network

Members: Arham, Matt, Alok, Valerie, Hai, Haochen
