# Example Sankey Diagram

This is an example of a Sankey diagram created using Mermaid.

```mermaid
%%{ init : { 'theme': 'base', 'themeVariables': { 'primaryColor': '#ffcc00', 'edgeLabelBackground':'#ffffff', 'tertiaryColor': '#e0e0e0' }}}%%
sankey
    A[Input]    --> B[Process 1]
    B          --> C[Process 2]
    C          --> D[Output 1]
    C          --> E[Output 2]
    A          --> F[Process 3]
    F          --> G[Output 3]
