# GDSC Unified App V2

- Don’t use any LLMs[^LLMs] for anything!
- This is a self-learning exercise.
  - **Don't ask Anurag or Thahir** for how to do things. Feel free to ask others. If Thahir finds out Anurag was asked, he will be very disappointed in you people.
  - You may ask Anurag or Thahir sparingly, for doubts regarding the instructions in this document. Remember, how you implement is your freedom. Thahir has only specified the requirements.

[^LLMs]: Large Language Models

## Project Requirements

### Database Features

- [ ] 3NF Normalization
- [ ] Minimal Tables
- [ ] High Performance

### App Features

- [ ] User Authentication
- [ ] GSheets Connectivity
- [ ] Interactive Graphs
- [ ] High Performance
- [ ] ~~ML~~ Not for now, since not enough data.

### Documentation

Text must be in markdown format; Diagrams must be in `svg` format

- [ ] ER Diagram of database
- [ ] Notes of each [technology](#technologies)
- [ ] Explanation of features
- [ ] Reason for method of implementations
- [ ] References used (use footnotes like how used here for LLMs[^LLMs]

## Technologies

You are expected to write

- Simplified explanation for each library. It's use-cases, advantages, disadvantages. Write in your own words. Do not use LLMs[^LLMs] for this.
- Why technology used
- Why technology not used. Feel free to document more if you come across something

| Technology         | Use                            | Not Use                                                      |
| ------------------ | ------------------------------ | ------------------------------------------------------------ |
| Database           | GSheets                        | SQL                                                          |
| App                | Streamlit                      | [Streamsync](https://medium.com/@ramiromedina/streamsync-like-streamlit-but-faster-and-with-a-visual-ui-editor-9f98ad17adf)<br />Dash |
| Dataframe          | [Polars](https://www.pola.rs/) | Pandas<br />Modin<br />Dask<br />Ray                         |
| Data Visualization | Plotly                         | Matplotlib<br />Seaborn<br />Altair<br />Plotnine<br />HVPlot<br />Bokeh |

## Reference

[App V1](https://gdscbpdc.streamlit.app/)
