Rakshan Patnaik - rapatnaik@ucsd.ed
DSC 180A - D37 Renu Raman

**What is the most interesting topic covered in your domain this quarter?** \
The most interesting topic covered in our domain is the idea of a data lake and how it can use knowledge agents to develop a semantic understanding, which can then get passed through as input to
knowledge consolidation agents, who can organize by domain and meaning, then bundle into shared resources, create plans out of those shared resources for common, complex questions, and then 
consolidate all those agents into an AI planning pipeline. I'm curious to understand how an agentic structure within a data lake can automatically generate deeper understandings from 
input datasets to then create reproducible workloads to probable questions of that dataset.

**Describe a potential investigation you would like to pursue for your Quarter 2 Project.** \
On top of this data lake, we will be building a text-to-sql product, so I want to further investigate how this data lake with interconnecting agents will help enable a more efficient
text-to-SQL pipeline. One of the biggest issues with text-to-SQL methodologies is that enterprise workloads are less accurate due to structural issues. I would investigate whether the
data lake structure we learnt with knowledge and knowledge consolidation agents can actually improve the join path failures or table-column mismatches, especially with the thorough JSON outputs
detailing the data dictionary that our agents create that nearly match our manually-written data dictionaries. 

**What is a potential change you’d make to the approach taken in your current Quarter 1 Project?** \
One change I would make to this approach taken in this quarter's project is that I want to focus more on how the metadata and semantic agents we've built will impact our downstream text-to-sql agent
and alter teh structure accordingly. Right now, for Quarter 1, we're building a data lake regarding the knowledge consolidation architecture that we got from our mentor Jack. I'm curious to see how that
architecture would change, if at all, if we consider the downstream products our capstone team will be building for quarter 2. 

**What other techniques would you be interested in using in your project?** \
One technique I'm interested in using would be RAG agents to improve how our agents identify relevant metadata and semantic relationships across datasets. Rather than providing an LLM with an 
entire data dictionary from the metadata agent, we could use embedding-based retrievals to identify the most relevant tables, columns, and relationships based on a user's natural language question. 
This could help reduce unrelated context and improve the accuracy of text-to-SQL generation, especially when working with more complex and multi-encompassing datasets.
