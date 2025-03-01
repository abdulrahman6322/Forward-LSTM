# LSTM Numerical Example

This repository contains a Python implementation of a simple LSTM (Long Short-Term Memory) network to predict the next value in a numerical sequence. The code follows a step-by-step numerical example to demonstrate how LSTMs work.

## Overview

The LSTM is a type of recurrent neural network (RNN) that is capable of learning long-term dependencies in sequential data. This implementation demonstrates the forward pass of an LSTM for a simple input sequence `[1, 2, 3]` and predicts the next value in the sequence.

### Key Features:
- **Step-by-step LSTM computation**: The code computes the forget gate, input gate, candidate cell state, cell state update, output gate, and hidden state update for each time step.
- **Modular implementation**: The LSTM operations are encapsulated in a class for better organization and reusability.
- **Prediction**: The final hidden state is used to predict the next value in the sequence using a linear transformation.
