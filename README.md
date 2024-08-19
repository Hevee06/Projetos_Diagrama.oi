# Flowcharts

### 🔰Overview

Remote storage area for flowcharts created on Draw.io site :)

```mermaid
    graph TD
    Start([Start]) --> Input([Input A])
    Input --> Read_B([Read B])
    Read_B --> Condition([A < B])
    
    Condition -->|true| B12([B = 12])
    Condition -->|false| Input([Input A])
    
    B12 --> Break([Break])
    
