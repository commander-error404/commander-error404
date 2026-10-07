<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:0d1117,50:0b3d1e,100:39FF14&text=commander-error404&fontColor=39FF14&fontSize=48&fontAlignY=38&desc=backend%20%C2%B7%20embedded%20%C2%B7%20automation&descSize=18&descAlignY=60&animation=fadeIn" alt="commander-error404 banner" width="100%"/>

```
 ███████╗██████╗ ██████╗  ██████╗ ██████╗     ██╗  ██╗ ██████╗ ██╗  ██╗
 ██╔════╝██╔══██╗██╔══██╗██╔═══██╗██╔══██╗    ██║  ██║██╔═████╗██║  ██║
 █████╗  ██████╔╝██████╔╝██║   ██║██████╔╝    ███████║██║██╔██║███████║
 ██╔══╝  ██╔══██╗██╔══██╗██║   ██║██╔══██╗    ╚════██║████╔╝██║╚════██║
 ███████╗██║  ██║██║  ██║╚██████╔╝██║  ██║         ██║╚██████╔╝     ██║
 ╚══════╝╚═╝  ╚═╝╚═╝  ╚═╝ ╚═════╝ ╚═╝  ╚═╝         ╚═╝ ╚═════╝      ╚═╝
```

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3200&pause=900&color=39FF14&center=true&vCenter=true&width=680&lines=%3E+backend%2C+embedded%2C+automation;%3E+writing+Go+without+an+ORM+(mostly);%3E+writing+Python+with+three+ORMs+(also+mostly);%3E+reinventing+wheels%2C+some+of+them+roll)](https://git.io/typing-svg)

<a href="https://github.com/commander-error404"><img src="https://img.shields.io/badge/GitHub-commander--error404-0d1117?style=for-the-badge&logo=github&logoColor=39FF14&labelColor=0d1117&color=39FF14" alt="GitHub"/></a>
<img src="https://komarev.com/ghpvc/?username=commander-error404&label=Profile+views&color=39ff14&style=for-the-badge&labelColor=0d1117" alt="Profile views"/>
<img src="https://img.shields.io/badge/Go-backend-0d1117?style=for-the-badge&logo=go&logoColor=00ADD8&labelColor=0d1117&color=00ADD8" alt="Go"/>
<img src="https://img.shields.io/badge/Python-everything-0d1117?style=for-the-badge&logo=python&logoColor=3776AB&labelColor=0d1117&color=3776AB" alt="Python"/>

</div>

<br/>

## `> whoami`

I build things at the intersection of software and hardware: REST APIs, embedded firmware, CNC controllers, and small services that hum at 3 AM and just work.

```go
package main

type Dev struct {
	Handle string
	Langs  []string
	Loves  []string
	Avoids []string
	Motto  string
}

func main() {
	me := Dev{
		Handle: "commander-error404",
		Langs:  []string{"Go", "Python", "C", "Rust", "Bash"},
		Loves:  []string{"REST APIs", "Kafka", "CNC & G-code", "embedded firmware"},
		Avoids: []string{"magic", "shortcuts", "ORMs I didn't write myself (mostly)"},
		Motto:  "Full accountability for every line.",
	}
	_ = me
}
```

> I have a habit of re-implementing tools that already exist. Not because the world needs another ORM, but because you don't really understand Django's ORM until you've written a worse one yourself, watched it explode on edge cases nobody warned you about, and then finally read the source with new appreciation.

Currently deep in Go. Gin for the API layer, `database/sql` and raw queries underneath, layered architecture, Kafka when things need to talk to each other asynchronously. No magic, no shortcuts, just full accountability for every line.

<br/>

## `> what-i-build`

Somewhere in the space between *"someone already made this"* and *"but I want to know how it works."*

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>🛠️ Non-standard implementations</h4>
      Homegrown ORMs, parsers, protocol handlers. Educational chaos, and worth every hour.
    </td>
    <td width="50%" valign="top">
      <h4>⚙️ Go backend services</h4>
      Gin, layered architecture (handlers, services, repositories), JWT with access and refresh tokens, MySQL without an ORM, WebSocket endpoints when REST isn't enough.
    </td>
  </tr>
  <tr>
    <td valign="top">
      <h4>🐍 Python everything</h4>
      FastAPI and Django APIs, Telegram bots with aiogram, Discord bots with discord.py, scrapers, automation scripts, and occasionally a full website when someone asks nicely.
    </td>
    <td valign="top">
      <h4>🦾 Robotics and CNC</h4>
      Stepper motors, motion controllers, G-code, and the deeply satisfying moment when metal moves exactly where the math said it would.
    </td>
  </tr>
  <tr>
    <td valign="top">
      <h4>🔁 Automation pipelines</h4>
      Scripts that run quietly for months until you forget they exist.
    </td>
    <td valign="top">
      <h4>🔌 Embedded systems</h4>
      Software that has to remember the real world exists (and occasionally disagrees with it).
    </td>
  </tr>
  <tr>
    <td colspan="2" valign="top">
      <h4>📨 Event-driven services</h4>
      Kafka producers/consumers, background workers, the occasional message that arrives twice and needs to be told it's not special.
    </td>
  </tr>
</table>

<br/>

## `> ls projects/`

<table>
  <tr>
    <td width="33%" valign="top">
      <h3>🚀 REST API<br/>with Go &amp; Gin</h3>
      <sub>High-performance REST API on Go and Gin.</sub>
      <br/><br/>
      ▸ Secure REST endpoints<br/>
      ▸ JWT authentication<br/>
      ▸ Request validation &amp; error handling<br/>
      ▸ PostgreSQL persistence<br/>
      ▸ Go best-practice project layout
      <br/><br/>
      <img src="https://skillicons.dev/icons?i=go,postgres,docker,git&theme=dark" alt="Go, PostgreSQL, Docker, Git"/>
      <br/>
      <img src="https://img.shields.io/badge/Gin-0d1117?style=flat-square&logo=go&logoColor=00ADD8" alt="Gin"/>
      <img src="https://img.shields.io/badge/JWT-0d1117?style=flat-square&logo=jsonwebtokens&logoColor=d63aff" alt="JWT"/>
    </td>
    <td width="33%" valign="top">
      <h3>🐳 Containerized<br/>Backend Service</h3>
      <sub>Docker from day one, modular by design.</sub>
      <br/><br/>
      ▸ Fast APIs with Go and Gin<br/>
      ▸ Linux dev &amp; deploy environment<br/>
      ▸ Admin tasks automated in Bash<br/>
      ▸ Modular, maintainable architecture
      <br/><br/>
      <img src="https://skillicons.dev/icons?i=go,docker,linux,bash,git&theme=dark" alt="Go, Docker, Linux, Bash, Git"/>
      <br/>
      <img src="https://img.shields.io/badge/Gin-0d1117?style=flat-square&logo=go&logoColor=00ADD8" alt="Gin"/>
    </td>
    <td width="33%" valign="top">
      <h3>🤖 Discord & Telegram Bot<br/>Sandboxed Execution</h3>
      <sub>Runs user commands in an isolated environment.</sub>
      <br/><br/>
      ▸ Docker-based process isolation<br/>
      ▸ Backend logic in Go<br/>
      ▸ Command handling &amp; auto-replies<br/>
      ▸ Hardened script execution
      <br/><br/>
      <img src="https://skillicons.dev/icons?i=go,docker,linux,discord&theme=dark" alt="Go, Docker, Linux, Discord"/>
      <br/>
      <img src="https://img.shields.io/badge/Gin-0d1117?style=flat-square&logo=go&logoColor=00ADD8" alt="Gin"/>
    </td>
  </tr>
</table>

<br/>

## `> cat stack.txt`

<table>
  <tr>
    <td width="170"><b>Languages</b></td>
    <td><img src="https://skillicons.dev/icons?i=go,py,c,rust,bash&theme=dark" alt="Go, Python, C, Rust, Bash"/></td>
  </tr>
  <tr>
    <td><b>Backend</b></td>
    <td>
      <img src="https://skillicons.dev/icons?i=fastapi,django,flask&theme=dark" alt="FastAPI, Django, Flask"/><br/>
      <img src="https://img.shields.io/badge/Gin-0d1117?style=flat-square&logo=go&logoColor=00ADD8" alt="Gin"/>
      <img src="https://img.shields.io/badge/SQLAlchemy-0d1117?style=flat-square&logo=sqlalchemy&logoColor=D71F00" alt="SQLAlchemy"/>
      <img src="https://img.shields.io/badge/Alembic-0d1117?style=flat-square&logo=alembic&logoColor=6BA539" alt="Alembic"/>
    </td>
  </tr>
  <tr>
    <td><b>APIs &amp; Protocols</b></td>
    <td>
      <img src="https://img.shields.io/badge/REST-0d1117?style=flat-square&logo=fastapi&logoColor=02569B" alt="REST"/>
      <img src="https://img.shields.io/badge/WebSocket-0d1117?style=flat-square&logo=socketdotio&logoColor=white" alt="WebSocket"/>
      <img src="https://img.shields.io/badge/JWT-0d1117?style=flat-square&logo=jsonwebtokens&logoColor=d63aff" alt="JWT"/>
    </td>
  </tr>
  <tr>
    <td><b>Messaging</b></td>
    <td><img src="https://skillicons.dev/icons?i=kafka&theme=dark" alt="Kafka"/></td>
  </tr>
  <tr>
    <td><b>Databases</b></td>
    <td><img src="https://skillicons.dev/icons?i=mysql,postgres,sqlite,mongodb,redis&theme=dark" alt="MySQL, PostgreSQL, SQLite, MongoDB, Redis"/></td>
  </tr>
  <tr>
    <td><b>Cloud &amp; DevOps</b></td>
    <td><img src="https://skillicons.dev/icons?i=aws,docker,nginx,linux,githubactions,git&theme=dark" alt="AWS, Docker, Nginx, Linux, GitHub Actions, Git"/></td>
  </tr>
  <tr>
    <td><b>Monitoring</b></td>
    <td><img src="https://skillicons.dev/icons?i=prometheus,grafana&theme=dark" alt="Prometheus, Grafana"/></td>
  </tr>
  <tr>
    <td><b>Testing</b></td>
    <td>
      <img src="https://skillicons.dev/icons?i=pytest&theme=dark" alt="Pytest"/>
      <img src="https://img.shields.io/badge/Testify-0d1117?style=flat-square&logo=go&logoColor=00ADD8" alt="Testify"/>
    </td>
  </tr>
  <tr>
    <td><b>Python bots &amp; scraping</b></td>
    <td>
      <img src="https://img.shields.io/badge/aiogram-0d1117?style=flat-square&logo=telegram&logoColor=2CA5E0" alt="aiogram"/>
      <img src="https://img.shields.io/badge/discord.py-0d1117?style=flat-square&logo=discord&logoColor=5865F2" alt="discord.py"/>
      <img src="https://img.shields.io/badge/BeautifulSoup-0d1117?style=flat-square&logo=python&logoColor=4B8BBE" alt="BeautifulSoup"/>
      <img src="https://img.shields.io/badge/Requests-0d1117?style=flat-square&logo=python&logoColor=white" alt="Requests"/>
    </td>
  </tr>
  <tr>
    <td><b>Hardware &amp; Embedded</b></td>
    <td>
      <img src="https://skillicons.dev/icons?i=arduino,raspberrypi&theme=dark" alt="Arduino, Raspberry Pi"/>
      <img src="https://img.shields.io/badge/ESP32-0d1117?style=flat-square&logo=espressif&logoColor=E7352C" alt="ESP32"/>
    </td>
  </tr>
</table>

<br/>

## `> git stats`

<div align="center">
  <img src="https://streak-stats.demolab.com/?user=commander-error404&theme=tokyonight&hide_border=true" alt="GitHub Streak" height="170"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=commander-error404&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages" height="170"/>
</div>

<br/>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=120&color=0:39FF14,50:0b3d1e,100:0d1117&section=footer&reversal=true" alt="footer" width="100%"/>
</div>
