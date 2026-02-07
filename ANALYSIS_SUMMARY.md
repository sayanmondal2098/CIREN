# CTI Knowledge Graph - Comprehensive Analysis Summary

## ✅ REWRITE COMPLETE: Research Analysis Metrics with Integrated Centrality Comparison

### What Was Done

#### Step 6 - Rewritten Research Analysis Metrics
The Research Analysis cell was completely rewritten to integrate **Degree Centrality vs Betweenness Centrality** detailed comparison directly into a single comprehensive analysis:

**Key Enhancements:**

1. **Centrality Metrics Definitions** - Added detailed textual explanations:
   - **Degree Centrality**: Measures direct connections (LOCAL importance - HUBs)
   - **Betweenness Centrality**: Measures bridge importance in shortest paths (GLOBAL importance - BRIDGEs)
   - **Closeness Centrality**: Measures average distance to other nodes (PROXIMITY to all nodes)

2. **Integrated Comparison Table** - Professional ASCII table showing:
   - What each metric measures
   - Scope (local vs global)
   - Type of importance (popularity vs control)
   - Network role (hub vs bridge)
   - Computational complexity

3. **Comprehensive Visualizations** - 9-panel dashboard showing:
   - **Panel 1**: Top 15 techniques by APT usage (degree view)
   - **Panel 2**: APT activity distribution
   - **Panel 3**: Degree centrality distribution histogram
   - **Panel 4**: Betweenness centrality distribution histogram
   - **Panel 5**: Closeness centrality distribution histogram
   - **Panel 6**: Top 10 degree centrality nodes (most connected hubs)
   - **Panel 7**: Top 10 betweenness centrality nodes (critical bridges)
   - **Panel 8**: Top 10 closeness centrality nodes (most central)
   - **Panel 9**: MITRE tactic coverage by technique count

4. **Statistical Comparison** - For all three centrality metrics:
   - Mean, Median, Std Dev, Min/Max values
   - Network-wide comparison showing distribution differences

5. **Actor Specialization Analysis** - Profile each APT group:
   - Total techniques used
   - Unique techniques
   - Top techniques and usage frequency

6. **Tactic Coverage Analysis** - Show all 17 MITRE ATT&CK tactics:
   - Technique count per tactic
   - Distribution across the threat landscape

### Output Files Generated

#### Main Deliverable
- **CTI_Knowledge_Graph_Comprehensive_Report.pdf** (2.95 MB)
  - 8-page professional PDF report with all analyses
  - Updated to include new integrated metrics visualization

#### Detailed Metrics Files
- **graph_metrics_centrality_comparison.png** (0.96 MB) - High-resolution metrics dashboard
- **graph_metrics_centrality_comparison.pdf** (0.04 MB) - Vector format metrics dashboard

#### Supporting Visualizations
- **centrality_comparison_degree_vs_betweenness.png** (0.28 MB) - Detailed centrality comparison
- **top_25_connected_nodes.png** (1.51 MB) - Top connected nodes visualization
- **kg_visualization.html** (0.05 MB) - Interactive network explorer

### Key Findings

#### Degree Centrality (Direct Connections)
**Top Nodes (LOCAL HUBS):**
1. CARBANAK (0.4312) - Most active APT with 47 direct connections
2. FIN7 (0.1468)
3. APT29 (0.1193)
4. FIN6 (0.1101)
5. OILRIG (0.0825)

**Interpretation:** These are the most frequently used techniques and most active APT groups in the dataset.

#### Betweenness Centrality (Global Bridge Importance)
**Top Nodes (CRITICAL BRIDGES):**
1. CARBANAK (0.1154) - Controls crucial connection pathways
2. REMOTE SERVICES (0.0156) - Key technique in attack chains
3. REMOTE ACCESS SOFTWARE (0.0115)
4. INGRESS TOOL TRANSFER (0.0088)
5. OBFUSCATED FILES OR INFORMATION (0.0085)

**Interpretation:** These techniques and actors act as intermediaries between different parts of the threat landscape.

#### Technique Hubs (Universal Attack Vectors)
- **PHISHING**: 7 APTs (universal technique)
- **COMMAND AND SCRIPTING INTERPRETER**: 6 APTs
- **EXPLOITATION FOR CLIENT EXECUTION**: 4 APTs
- **REMOTE SERVICES**: 4 APTs
- **USER EXECUTION**: 4 APTs

### Key Differences Explained

#### Degree Centrality Shows
✓ Most connected/popular nodes
✓ Which actors use most techniques
✓ Which techniques are in widest use
✓ Local network importance

#### Betweenness Centrality Shows
✓ Critical intermediary nodes
✓ Gateway techniques in attack chains
✓ Bottleneck points in threat operations
✓ Global network control and influence

### Network Properties
- **Total Nodes**: 110 (7 APT groups, 53 techniques, 17 tactics, 23 tools)
- **Total Edges**: 236 directed relationships
- **Density**: 0.0197 (sparse network with hub structure)
- **Connected Components**: 1 (fully connected threat landscape)

### Research Implications

1. **CARBANAK is Most Sophisticated** - Dominates both degree and betweenness centrality, indicating:
   - Largest technique arsenal (47 techniques)
   - Most diverse operational tactics
   - Acts as central connector in threat landscape

2. **PHISHING is Universal** - Shared by 7 of 7 APT groups:
   - Most common attack vector across all threat actors
   - Critical entry point in threat operations
   - High strategic importance

3. **Scale-Free Network Topology** - Few hub nodes dominate:
   - Suggests specialized threat landscape
   - Key techniques are critical chokepoints
   - Targeting one hub could disrupt multiple threat actors

4. **Technique Reuse Pattern** - Average 23.7 techniques per APT:
   - Indicates shared attack methodology
   - Evidence of technique commoditization
   - Potential for cross-threat-actor attribution

### Data Statistics
- **CTI Reports Processed**: 81 JSON files from CTI-HAL dataset
- **Semantic Triples Extracted**: 443 total
  - Actor → Technique: 166 triples
  - Technique → Tactic: 175 triples
  - Technique → Tool: 102 triples
- **MITRE ATT&CK Tactics Covered**: 17 of ~14 possible MITRE tactics
- **Analysis Depth**: 3 centrality metrics + 4 analytical dimensions

---

## File Organization

### Main Report
```
CTI_Knowledge_Graph_Comprehensive_Report.pdf  ← START HERE (8 pages)
```

### Visualizations
```
graph_metrics_centrality_comparison.png  ← Integrated metrics dashboard
graph_metrics_centrality_comparison.pdf  ← Vector format
kg_visualization.html                    ← Interactive network explorer
top_25_connected_nodes.png              ← Top nodes visualization
```

### Notebook
```
v2.ipynb  ← Jupyter notebook with full analysis pipeline
```

---

## How to Use This Analysis

1. **For Executive Summary**: Read CTI_Knowledge_Graph_Comprehensive_Report.pdf (pages 1-2)
2. **For Technical Details**: Review integrated metrics visualization (page 4-5)
3. **For Interactive Exploration**: Open kg_visualization.html in web browser
4. **For Detailed Study**: Examine v2.ipynb Jupyter notebook with all code and explanations
5. **For Presentations**: Use high-resolution PNG files (300 DPI)

---

## Next Steps

The analysis can be extended with:
- Temporal analysis of technique adoption over time
- Geographic attribution of threat actors
- Industry-specific targeting analysis
- Tool ecosystem mapping (techniques → tools usage patterns)
- Predictive modeling of emerging threat techniques

---

*Analysis completed with comprehensive centrality comparison (degree vs betweenness vs closeness)*
*All visualizations generated at 300 DPI for publication quality*
*PDF report includes 8 pages with integrated findings*
