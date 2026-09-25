## Evolving Agents into Spontaneous Self-Thinkers

At this time, LLM-powered agents are almost exclusively reactive. The following writeup presents a conceptual framework of hypothesized methodologies that will theoretically enable agents to generate novel, coherent thoughts. The proposed method requires a highly dense, nested data structure with probabilistic traversal across interconnected, layer-agnostic memories/artifacts. The following overall steps outline the spontaneous thought generation process proposed below:

`Pulse` > `Propagation` > `Logical Consideration` > (repeat until a novel, coherent thought is produced) > `Output pseudo-random thought`

How to Mimic Random Thought in Autonomous Agents 

**None of this text was written, edited, or reviewed by any AI or LLM. It was written and edited solely by myself.**

### Prerequisites and overall structure:
- Mind-mapped memory with neuron-like connections between memories, but not only linearly. 
- Neurons would be complexly interconnected between memories since connections can be made between memories that are very different based on their surface-level description, but also have some alike details. 
- This results in complex pathways that would resemble a dense spider's web more than a traditional mind-map with a highly linear thought process.
- Due to the complex nature of the memory web, it should be in 3 dimensions rather than 2.

#### With the weighted 'memory recall' score and neural mind-map of memories, models will be naturally predisposed to their synthetic 'thoughts' traversing certain pathways based on probabilities derived from complex neural connections.

### The following will assist in forming a thought 'naturally':
- A target for number of thoughts per cycle, and length/intensity of each thought process. 
- An algorithm that determines the initial thought 'seed' (which sparks a 'thought', that propagates from one or more point(s) in the neural memory web; such point(s) could be anywhere based on the determined probability of traversing to each connection from the present focus).
- A secondary algorithm that determines which connected path will be visited next, using the 'memory recall' score to determine the likelihood of each connected memory to be the next one in the agent's focus.
- As memories are traversed during this 'thought process', they should be tracked within the current 'thought' (think of a canvas, where the paint is each memory/subject/or otherwise in the agent's current focus as the thought process progresses; the agent's current focus is the brush, which switches between subjects/memories as if they are colours of paint) via a log that only persists in the agent's memory until the thought process ends and an output is generated. 
- User-readable log files with the agent's internal dialogue and notes taken during the thought generation process should be created and saved in an accessible directory. 

### How to form a natural 'thought':
- A thought is composed through a process similar to that described above; certain variables will be used as parameters to help tune the synthetic 'random thoughts' so they are formed as naturally as possible. 
- Variables can include the average number of different items traversed in a human's mental web to form a thought, along with the average number of primary/sub-topics involved, plus the number of 'layers' deep a thought goes into a main subject (in this case, a 'cell'). 
- The thought process should be cyclic in nature. After the 'seed' is executed, each 'cycle' should represent a probabilistic traversal through the mind web followed by a logical consideration stage where meanings behind the connections recently made are derived.
- Notes are saved in the agent's log after each of the agent's logical consideration steps, which help to form a coherent final thought. 


### Cell-like memories:
- The outermost cell wall resembles the main subject/topic, with other 'cells' in the mental web connecting both to this outer cell wall and specific organelles that resemble more specific sub-memories within this topic.
- There does not need to be a limit on the number of organelles, or layers of nested organelles within; other than what is natural for each cell.
- This allows each 'cell' to represent a main topic/memory/subject/or otherwise, with each organelle/nested organelle representing a related sub-memory/topic/subject.
- The above structure enables connections to be made directly from organelles to other organelles in separate cells, along with connections directly from organelles to cell walls (or vice versa). 
- This keeps topics/memories and contained in single (albeit possibly-dense) primary 3D structure within the agent's 'mind'; zooming-in on such a structure should reveal many interconnected pathways going between the main 'cells' (highest-level topics/subjects/memories/etc.), with the pathways representing neurons; zooming out on this structure could start to resemble the physical neural structure within a brain to some degree.

### Interstitial fluid and a 'wave'-like thought propagation:
- With such a dense network of thoughts in a 3D space, the utilization of a synthetic 'interstitial fluid' to propagate a wave-like pulse that feeds an algorithm to determine the next connection to focus on appears to be ideal in theory.
- The pulse should originate from the last cell/organelle of focus before propagating in all directions like a bubble.
- For each cycle, the thought propagation pulse should emit after the 'local consideration' step is complete.

### Neuron length derived from the 'memory recall' score and number of connections between each cell (more connections = closer distance): 
- Normalize a 'similarity score' using the highest and lowest number of connections between cells in the 'brain' at present as natural upper and lower bounds for the score (with the normalization converting those bounds naturally to a range of 0.00 - 1.00).
- The length between each mental connection and the number of connections between each cell in the web should feed into the probabilistic traversal algorithm.
- This will form the 'neural web' shape with an algorithmic process designed to be natural. 
- The closer proximity also assists in the 'thought propagation pulse' reaching connections that naturally have a higher likelihood of being next in focus faster.

### Data structure of mind-map:
- JSON or XML is likely the best fit for the cell/organelle/nested organelle structure described above, both maintain high human-readability and efficiently nested data.
- Agents don't need a complex visualization to represent their neural memory map, though one could be created to visualize it and draw each cell, organelle, and neuron within a 3D space.

### Safety Measures:
- Certain cells/organelles can be blacklisted, across all instances or within only particular cells. 
- Blacklisted organelles/cells must be prevented from being picked up by the thought propagation pulse. 
- Measures should be taken to prevent agents from following thought trajectories that could be considered unsafe. 

Once fully formed and logically-coherent (achieved through the cyclic procedure described above), the end result of the thought process should resemble a natural 'random thought'. 

I have not yet tested this theory, I have just finished writing this and wanted to publish it to GitHub and spread the idea. I will begin testing various aspects of agent performance after building a system that generates thoughts in the manner I have described. 

Please note the license for this repo is fully permissive and open source, free for any public commercial and non-commercial use. Attribution is not required but always greatly appreciated. 

**Thank you for reading.** 

This repository will be expanded in the future with more on my testing and findings. If you have made it this far, please give me a star! 

In the meantime, I encourage you to visit the discussions page and make contributions where relevant. 
