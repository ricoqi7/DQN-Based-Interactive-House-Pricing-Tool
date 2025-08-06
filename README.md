# DQN-Based-Interactive-House-Pricing-Tool
 A reinforcement learning-based system that suggests dynamic house price adjustments. Supports numerical and textual property features with Early Fusion, Late Fusion, and Attention-Based Fusion strategies. Interactive, explainable, and designed for practical pricing scenarios.

# DQN-Based Interactive House Pricing Tool

This project presents an interactive real estate pricing tool powered by Deep Q-Networks (DQN), designed to assist users in determining optimal house price adjustments based on property features. By integrating reinforcement learning with multi-modal data (numerical + textual descriptions), this tool provides intelligent, context-aware pricing suggestions.

## Key Features
- **Reinforcement Learning-Based Pricing**: Uses DQN to suggest price adjustment percentages.
- **Supports Multi-Modal Data**: Incorporates numerical attributes and SBERT-encoded text descriptions.
- **Three Fusion Strategies**:
  - Early Fusion (feature concatenation)
  - Late Fusion (separate sub-networks)
  - Attention-Based Fusion (adaptive gating)
- **Interactive User Interface**: Input property features and receive pricing recommendations.
- **Baseline Comparisons**: Evaluated against traditional Linear Regression models.

## Dataset Sources
- **Beijing Housing Price Data (2011-2017)**
- **Chicago Real Estate Listings (2022-2024)**
- **Melbourne Housing Dataset (Experimental Validation)**

## Project Structure
- `DQN_v2.ipynb`: Numerical feature-based DQN baseline.
- `DQN_v4.ipynb`: Model generalization on new datasets.
- `DQN_v4.1.ipynb`: Early Fusion architecture.
- `DQN_v4.2.ipynb`: Late Fusion architecture.
- `DQN_v4.3.ipynb`: Attention-Based Fusion with gating mechanism.
- `utils/`: Helper functions (data processing, visualization).

## How to Use
1. Clone this repository.
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the notebook versions (`.ipynb`) for step-by-step training & testing.
4. Use the interactive module to input property details and get price adjustment suggestions.

## References
- Kemmer L., et al. *Reinforcement Learning for Supply Chain Optimization*, 2018.
- Md Hasebul Hasan et al., *A Multi-Modal Deep Learning Based Approach for House Price Prediction*, 2020.
- [Hossein-Alibandehloo/Dynamic-Pricing-with-Reinforcement-Learning (GitHub)](https://github.com/Hossein-Alibandehloo/Dynamic-Pricing-with-Reinforcement-Learning)
