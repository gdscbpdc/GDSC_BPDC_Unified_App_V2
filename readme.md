# GDSC Unified App V2

- Ensure to make GDSC account the owner for all assets, documents, designs, etc. Use your personal accounts for accessing
- Feel free to create a copy of everything to your personal account for your future reference
- Don’t use any LLMs[^LLMs] for anything!
- This is a self-learning exercise.
  - **Don't ask Anurag or Thahir** for how to do things. Feel free to ask others. If Thahir finds out Anurag was asked for help, he will be very disappointed.
  - You may ask Anurag or Thahir sparingly, only for doubts regarding the instructions in this document.
  - Remember, how you implement is your freedom. Thahir has only specified the requirements and has given proposed tools.

[^LLMs]: Large Language Models

## Documentation

Everything must be documented as simple and precise as possible, in their own files (already created). Write everything in your own words. Do not use LLMs[^LLMs] for this.

Text must be in markdown format; Diagrams must be in `svg` format

- [ ] ER Diagram of database
- [ ] Notes for technologies used as mentioned
  - Simplified explanation for each library. Its use-cases, advantages, disadvantages. 
  - Why tool used
  - Why tool not used. Feel free to document other tools if you come across something better/worse
- [ ] Explanation of features
- [ ] Reason for method of implementations
- [ ] References used
  - Use Reference Manager
  - Use Footnotes like how used here for LLMs[^LLMs]

## Requirements

### Database Features

- [ ] 3NF Normalization
- [ ] Minimal Tables
- [ ] High Performance

### App Features

- [ ] User Authentication
- [ ] GSheets Connectivity
- [ ] Appropriate Caching
- [ ] Optimized dataframe operations
- [ ] Interactive Graphs
- [ ] High Performance
- [ ] ~~ML~~ Not for now, since not enough data.
- [ ] Hosted online, preferably on [streamlit share](https://share.streamlit.io/).

### Proposed Tools

Ensure to stick to only open-source tools (GSheets is the only exception).

| Purpose         | Tool to Use                            | Tool to Not Use                                                      |
| ------------------ | ------------------------------ | ------------------------------------------------------------ |
| Database           | GSheets                        | SQL                                                          |
| App                | Streamlit                      | [Streamsync](https://medium.com/@ramiromedina/streamsync-like-streamlit-but-faster-and-with-a-visual-ui-editor-9f98ad17adf)<br />Dash |
| Dataframe          | [Polars](https://www.pola.rs/) | Pandas<br />Modin<br />Koalas<br />Dask<br />Ray                         |
| Data Visualization | Plotly                         | Matplotlib<br />Seaborn<br />Altair<br />Plotnine<br />HVPlot<br />Bokeh |
| Diagramming  | Draw.io                         | Canva                                                     |
| Reference Manager  | Zotero                         | Mendeley                                                     |

## Reference App

[App V1](https://gdscbpdc.streamlit.app/) by Ahmed Thahir

