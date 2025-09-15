<div style="display: flex; flex-direction: column;">
    <table align="center">
        <tr>
            <td>
                <img src="./public/assets/logos/awhere.svg" alt="⧊where Logo" width="100"/>
            </td>
            <td>
                <h1>⧊where (awhere)<sup>*</sup>: Agents Anywhere</h1>
                <p><em>An agentic platform for building agentic organizations.</em></p>
            </td>
        </tr>
        <tr>
            <td colspan="2">
                <sub>* ⧊where (awhere) is pronounced <i>aware</i> (uh-wehr).</sub>
            </td>
        </tr>
    </table>
</div>

<!--
Badges to be added here.
-->

⧊where is a platform for building agentic organizations—collaborative digital environments where intelligent agents and humans come together to iteratively build systems that transform creative ideas into measurable value outcomes.

The platform is born out of our firm belief in the role of _human beings as idea generators_ and the role of _organizations as playgrounds_ for implementation and experimentation of ideas generating value.

### Our Vision

We believe in the power of ideas, and we want to empower anyone to turn their ideas into reality—removing the barriers of access and availability of technical expertise through secure and verifiable agent based systems.

### Core Ideas

```mermaid
flowchart TD
    ideas@{ shape: stadium, label: "Core Ideas" }
    idea-to-production@{ shape: tag-rect, label: "Idea to <br> Production" }
    models-to-adaptive-systems@{ shape: tag-rect, label: "Models to <br> Adaptive Systems" }
    composable-actions-to-complex-behaviors@{ shape: tag-rect, label: "Composable Actions to Complex Behaviors" }
    conversational-agents-to-collaborative-workspaces@{ shape: tag-rect, label: "Conversational Agents to Collaborative Workspaces" }
    live-playgrounds@{ shape: tag-rect, label: "Live Playgrounds to Scenario Builders" }
    ideas --> idea-to-production
    ideas --> models-to-adaptive-systems
    ideas --> composable-actions-to-complex-behaviors
    ideas --> conversational-agents-to-collaborative-workspaces
    ideas --> live-playgrounds
```

The core ideas of ⧊where platform are:

1. **Idea to Production**: Ability to start from simple descriptions of ideas to production-ready systems.
   ```mermaid
   flowchart TB
    idea@{ shape: manual-input, label: "Input Ideas" }
    subgraph Awhere
        direction TB
        arun@{ shape: lin-rect, label: "Awhere Runtime" }
        subgraph Generated
            direction TB
            specs@{ shape: docs, label: "Specifications" }
            models@{ shape: lin-cyl, label: "Models" }
            subgraph Automation
                direction TB
                actions@{ shape: processes, label: "Actions" }
                agents@{ shape: processes, label: "Agents" }
                workflows@{ shape: processes, label: "Workflows" }
                actions --o agents
                actions --o workflows
            end
            specs -- models
            models --> Automation
        end
        subgraph Deployments
            direction TB
            playground@{ shape: hex, label: "Playground" }
            production@{ shape: hex, label: "Production" }
            playground -->|Publish| production
        end
        arun -->|Generate| Generated
        arun -->|Run| playground
    end
    idea eip@==> Awhere
    eip@{ animate: true }
   ```
2. **Composable Actions to Complex Behaviors**:
3. **Models to Adaptive Systems**:
4. **Live Playgrounds to Scenarios Generation**:
5. **Conversational Agents to Collaborative Workspaces**:

---

<span style="font-size:4pt; color: #666;">Copyright &copy; 2025 Weavers @ Eternal Loom. All rights reserved.</span>
