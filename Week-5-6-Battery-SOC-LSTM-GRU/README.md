# Week 5 & Week 6

## Battery State of Charge (SOC) Estimation using Deep Learning

### Objective

The objective of this phase of the internship was to estimate Battery State of Charge (SOC) using recurrent neural networks across multiple lithium-ion battery chemistries.

---

## Datasets

- LG HG2 (NCA)
- HUST (LFP)
- NASA PCoE (Li-ion)
- Tongji EV (NMC)

---

## Deep Learning Models

- Long Short-Term Memory (LSTM)
- Gated Recurrent Unit (GRU)

---

## Workflow

- Data preprocessing
- Feature selection
- SOC calculation
- Min-Max normalization
- Sequence generation
- LSTM training
- GRU training
- Performance evaluation using Loss, MAE and RMSE
- Cross-dataset comparison

---

## Summary

A comparative analysis was performed across four battery chemistries. Both LSTM and GRU models successfully estimated battery SOC. GRU achieved the best performance on three datasets, while LSTM performed best on the HUST (LFP) dataset.
