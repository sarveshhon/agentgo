# AgentGo
I recently built a lightweight AI agent in Go using the Google Agent Development Kit (ADK) that fetches real-time weather for any city. It’s a simple but powerful demo of how ADK can be used with custom tools and agents—even outside Python ecosystems.

## Screenshots

![App Screenshot](screenshots/image1.png)

## AgentGo Demo Video
<div style="display: inline-flex; align-items: center;">
  <a href="https://youtu.be/O32zQwxmixI" target="_blank" style="display: inline-block;">
    <img src="screenshots/image1.png" style="width: 100%; display: block;">
  </a>
</div>


## Usage
```bash git clone https://github.com/yourusername/go-weather-agent
cd agentgo
go mod tidy
go run agent.go web api webui
# Access webui at http://localhost:8080/
```
