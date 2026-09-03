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
.NET developer. I build web APIs and browser front ends in C#, and ship them as
containers on AWS.

Day to day I work on a commercial product whose repos are private, so this
profile is quieter than the work is. Below is the stack I actually use and one
public project that shows how I put it together.
### Shipped

📱 [Google Play](https://play.google.com/store/apps/dev?id=7857086275026745802) ·
[App Store](https://apps.apple.com/jo/developer/alaa-omar/id1736309763)

**Platinum suite** — mobile clients for the Platinum ERP platform
`Platinum HR` · `Platinum CRM` · `Platinum Owner` · `Platinum Label Printer` · `Platinum Uploader`

**Retail & marketplace** — storefront apps for supermarket and mall operators
`Food Gate Market` · `اسواق الثقافة` · `Emran Mall` · `Bustanji Mall` · `Premier Supermarket`

**Operations** — warehouse and order-handling tools
`Purchase Order Receive` · `Captain Order`

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

Modernizing **Platinum ERP** — a commercial ERP suite running in production for
around 1,000 businesses across Jordan. I'm rebuilding the legacy codebase into a
cleaner, properly structured, modern .NET application, across every domain in
the product.

The hard part isn't writing the new code. It's replacing the foundation of a
system a thousand companies run their daily operations on, without breaking what
already works for them.

### Contact

[LinkedIn](https://www.linkedin.com/in/omarwalid135/) · Omarwal71995@gmail.com
