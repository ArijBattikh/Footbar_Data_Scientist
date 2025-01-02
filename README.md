## Description

The goal of this project is to recreate a football match from accelerometer data collected from players during a game session. This data includes the norm of the 3D acceleration of the players' legs, along with the actions performed during each movement period. 
The model must analyze this data to identify actions (such as shots, passes, dribbles, etc.) and reconstruct them into logical sequences to simulate a realistic football game.

## Project Objectives

1. **Data Exploration**:
   - Analyze the provided accelerometer data to understand the relationship between different types of actions and their characteristics.
   - Identify distinctive patterns or features of various actions such as dribbles, shots, passes, etc.

2. **Game Recreation**:
   - Develop a model capable of generating action sequences to recreate a football game from accelerometer data.
   - Ensure that the generated sequences have temporal coherence and realistic progression, taking into account the duration of each gait period and the nature of the actions.

3. **Game Generation**:
   - Parameterize the game generator to produce games of various lengths (e.g., 15 minutes, 20 minutes, 60 minutes).
   - Implement specific playstyles such as attacking, defensive, or normal by adjusting the frequency of actions like passes, shots, tackles, etc.

4. **Preprocessing and Post-processing**:
   - Apply preprocessing techniques to clean the data (normalization, filtering out abnormal gait lengths).
   - Ensure input and output data consistency, avoiding unrealistic or inconsistent actions.

5. **Model Evaluation**:
   - Evaluate the generated games in terms of temporal and logical coherence of actions.
   - Check that the action sequence generated accurately reflects the chosen style of play.

