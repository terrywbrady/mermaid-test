{% include mermaid.html %}

# mermaid-test

{% include start.html %}
```
graph TD
  A[Client] --> B[Load Balancer]
  B --> C[Server01]
  B --> D[Server02]
  style B fill:yellow
```  
{% include end.html %}
