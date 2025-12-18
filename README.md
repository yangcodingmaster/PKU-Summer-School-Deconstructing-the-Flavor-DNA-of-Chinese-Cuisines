# Deconstructing the "Flavor DNA" of Chinese Cuisines: A PageRank-Based Analysis

This project was developed as a final assignment for the course **"Artificial Intelligence: Principles, Algorithms, and Applications"** at the **Peking University (PKU) Summer School (July 2025)**.

## Project Overview
Traditional analysis of Chinese culinary traditions often relies on qualitative descriptions and subjective experience. This project introduces a quantitative framework by adapting Google’s **PageRank algorithm** to model ingredient relationships. By constructing an "Ingredient Co-occurrence Network," we successfully identified and quantified the "Flavor DNA" of six major Chinese cuisines.

## Key Features
- **Quantitative Modeling**: Transforms traditional recipes into a mathematical graph where ingredients are nodes and co-occurrences are edges.
- **Core Ingredient Identification**: Uses the PageRank algorithm to calculate the "centrality" or importance of ingredients in different cuisines (Shandong, Cantonese, Sichuan, Huaiyang, Shanghai, and Northeastern).
- **"Sugar" as a Tracer**: A comparative study on the role of sugar across regions, challenging the "Sweet South, Salty North" stereotype through data.
- **Interactive Visualizations**: Includes PageRank distribution charts and interactive geographical heatmaps using Folium.

## Methodology
1. **Data Collection**: Selected 48 representative recipes across 6 major Chinese cuisines.
2. **Network Construction**: 
   - **Nodes**: Ingredients (e.g., Ginger, Chili, Soy Sauce).
   - **Edges**: Co-occurrence in the same recipe (weighted by frequency).
3. **Algorithm**: Applied the PageRank algorithm with a damping factor (d=0.85) to iterate and converge on the "importance" score for each ingredient.
4. **Analysis**: Compared Top-K ingredients and performed cross-cuisine correlation analysis.

## Key Insights
- **Sichuan (Chuan)**: Chili and Sichuan Pepper form the absolute core, confirming the "Mala" (numb and spicy) identity.
- **Huaiyang**: High centrality of "Stock" (Gao Tang) and "Ham" reflects the pursuit of extreme Umami.
- **Sugar Analysis**: Data shows that sugar's importance in Northern Shandong (Lu) cuisine is surprisingly high, comparable to the "sweet-labeled" Shanghai (Benbang) cuisine, but serving different flavor balancing roles.

## Contributors
* **Team Members**: Zhao Yang (UCL), Cai Yufan (PKU), Zhang Jiahe(XJTLU), Li Yutong(CUC), Tian Zixuan(UniMelb).
* **Institution**: Peking University (PKU)
