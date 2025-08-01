# SwarmsClient

Methods:

- <code title="get /">client.<a href="./src/swarms_client/_client.py">get_root</a>() -> object</code>

# Health

Types:

```python
from swarms_client.types import HealthCheckResponse
```

Methods:

- <code title="get /health">client.health.<a href="./src/swarms_client/resources/health.py">check</a>() -> <a href="./src/swarms_client/types/health_check_response.py">HealthCheckResponse</a></code>

# Agent

Types:

```python
from swarms_client.types import AgentCompletion, AgentSpec, AgentRunResponse
```

Methods:

- <code title="post /v1/agent/completions">client.agent.<a href="./src/swarms_client/resources/agent/agent.py">run</a>(\*\*<a href="src/swarms_client/types/agent_run_params.py">params</a>) -> <a href="./src/swarms_client/types/agent_run_response.py">AgentRunResponse</a></code>

## Batch

Types:

```python
from swarms_client.types.agent import BatchRunResponse
```

Methods:

- <code title="post /v1/agent/batch/completions">client.agent.batch.<a href="./src/swarms_client/resources/agent/batch.py">run</a>(\*\*<a href="src/swarms_client/types/agent/batch_run_params.py">params</a>) -> <a href="./src/swarms_client/types/agent/batch_run_response.py">BatchRunResponse</a></code>

# Models

Types:

```python
from swarms_client.types import ModelListAvailableResponse
```

Methods:

- <code title="get /v1/models/available">client.models.<a href="./src/swarms_client/resources/models.py">list_available</a>() -> <a href="./src/swarms_client/types/model_list_available_response.py">ModelListAvailableResponse</a></code>

# Swarms

Types:

```python
from swarms_client.types import (
    SwarmSpec,
    SwarmCheckAvailableResponse,
    SwarmGetLogsResponse,
    SwarmRunResponse,
)
```

Methods:

- <code title="get /v1/swarms/available">client.swarms.<a href="./src/swarms_client/resources/swarms/swarms.py">check_available</a>() -> <a href="./src/swarms_client/types/swarm_check_available_response.py">SwarmCheckAvailableResponse</a></code>
- <code title="get /v1/swarm/logs">client.swarms.<a href="./src/swarms_client/resources/swarms/swarms.py">get_logs</a>() -> <a href="./src/swarms_client/types/swarm_get_logs_response.py">SwarmGetLogsResponse</a></code>
- <code title="post /v1/swarm/completions">client.swarms.<a href="./src/swarms_client/resources/swarms/swarms.py">run</a>(\*\*<a href="src/swarms_client/types/swarm_run_params.py">params</a>) -> <a href="./src/swarms_client/types/swarm_run_response.py">SwarmRunResponse</a></code>

## Batch

Types:

```python
from swarms_client.types.swarms import BatchRunResponse
```

Methods:

- <code title="post /v1/swarm/batch/completions">client.swarms.batch.<a href="./src/swarms_client/resources/swarms/batch.py">run</a>(\*\*<a href="src/swarms_client/types/swarms/batch_run_params.py">params</a>) -> <a href="./src/swarms_client/types/swarms/batch_run_response.py">BatchRunResponse</a></code>

# ReasoningAgents

Types:

```python
from swarms_client.types import (
    ReasoningAgentCreateCompletionResponse,
    ReasoningAgentListTypesResponse,
)
```

Methods:

- <code title="post /v1/reasoning-agent/completions">client.reasoning_agents.<a href="./src/swarms_client/resources/reasoning_agents.py">create_completion</a>(\*\*<a href="src/swarms_client/types/reasoning_agent_create_completion_params.py">params</a>) -> <a href="./src/swarms_client/types/reasoning_agent_create_completion_response.py">ReasoningAgentCreateCompletionResponse</a></code>
- <code title="get /v1/reasoning-agent/types">client.reasoning_agents.<a href="./src/swarms_client/resources/reasoning_agents.py">list_types</a>() -> <a href="./src/swarms_client/types/reasoning_agent_list_types_response.py">ReasoningAgentListTypesResponse</a></code>

# Client

## Rate

Types:

```python
from swarms_client.types.client import RateGetLimitsResponse
```

Methods:

- <code title="get /v1/rate/limits">client.client.rate.<a href="./src/swarms_client/resources/client/rate.py">get_limits</a>() -> <a href="./src/swarms_client/types/client/rate_get_limits_response.py">RateGetLimitsResponse</a></code>
