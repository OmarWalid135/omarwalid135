## Omar Walid

.NET developer. I build web APIs and browser front ends in C#, and ship them as
containers on AWS.

Day to day I work on a commercial product whose repos are private, so this
profile is quieter than the work is. Below is the stack I actually use and one
public project that shows how I put it together.

### Public work

**[Carseer](https://github.com/OmarWalid135/Carseer2)** — vehicle lookup app
over the NHTSA vPIC database. Pick a make and model year, get back the vehicle
types and models.

- **Blazor WebAssembly** front end — the whole UI runs in the browser, in C#
- **ASP.NET Core Web API** in front of vPIC — proxies the public API and caches
  responses, so repeated lookups don't hit an external service the app doesn't
  control and can't rely on for latency
- **Docker + Docker Compose** for local runs, deployed to **AWS ECS** behind an
  **Application Load Balancer**

The interesting part isn't the UI, it's the layer between it and vPIC: a third
party API you can't change, wrapped in something with predictable latency and a
failure mode you own.

### What I work with

**Languages** — C#, JavaScript, HTML/CSS, SQL
**Backend** — .NET 8, ASP.NET Core, Web API, Entity Framework
**Frontend** — Blazor WebAssembly
**Infrastructure** — Docker, Docker Compose, AWS (ECS, ALB)
**Practice** — Git, pull requests, code review

### Currently

Working on <what you're building / learning right now — one line>.

### Contact

[LinkedIn]([https://www.linkedin.com/in/omarwalid135/]) · Omarwal71995@gmail.com

Everything above the placeholders is grounded in Carseer2's actual README — .NET 8, Blazor WASM, the caching proxy, Compose, ECS, ALB. I deliberately claimed no metrics and no job title, because inventing "cut latency 60%" on a profile is the fastest way to get caught in an interview.
 
