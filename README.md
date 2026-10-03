<!-- Course: this file IS your setup instructions. First drafted in Stage 1,
     rewritten in Stage 3 when a classmate has to run your app from it without
     asking you anything. See docs/course/DELIVERABLES.md -->


# PROJECT NAME: nAvI 

A web app that helps travel-lovers generate destinations, itineraries, budgets, and packing lists based on as simple as a given vibe.

## What it does

nAvI helps elevate the stress that goes into traveling. This spans from planning the trip from scratch, like suggesting destinations and estimate budgets, to curating a trip based on a vibe. This tool replaces hours of research across several sites with a faster and personalized site. 

## Screenshot

<!-- Add one once you have something to show. A picture answers "what is this"
     faster than any paragraph. -->

---

## Setup

**Everything a stranger needs, in order.** Test this by handing it to someone
and watching them. Every question they ask is a bug in this section.

### You will need

- Render account
- Neon account
- TensorX API
- ChatGPT
  

### Steps

```bash
# 1. Get the code
git clone <YOUR REPO URL>
cd <YOUR REPO NAME>

# 2. Install what it needs
cd src/backend
npm install

cd ../frontend
npm install

# 3. Set environment variables
# Create src/backend/.env and add:
# OPENAI_API_KEY=...
# TENSORX_API_KEY=...
# DATABASE_URL=...
# PLACES_API_KEY=...
# UNSPLASH_API_KEY=...

# 4. Run it
# Backend:
cd src/backend
npm start

# Frontend:
cd ../frontend
npm run dev

```

Then open <!-- e.g. http://localhost:8501 --> in your browser.

### Running the tests

```bash
# (fill in: the one command that runs your whole test suite)
```

Every test should pass. If one fails, that is the app telling you something is
broken. Read what it says before changing anything.

---

## Project status

<!-- Update this each stage. It is the fastest way for anyone (including you in
     six weeks) to know where things stand. -->

**Current version:** pre-alpha
**Working:** nothing yet
**Not working yet:** see [docs/backlog.md](docs/backlog.md)

## How this project is organized

| Where | What's in it |
|---|---|
| [`docs/proposal.md`](docs/proposal.md) | The problem this solves and who it's for |
| [`docs/backlog.md`](docs/backlog.md) | Every feature, in build order, with its acceptance criteria |
| [`specs/`](specs/) | One page per feature: what it does, what it doesn't, what "done" means |
| [`AGENTS.md`](AGENTS.md) | The rules every AI assistant must follow in this repo |
| `src/` | The code |
| `tests/` | The automatic tests |
| [`CHANGELOG.md`](CHANGELOG.md) | What changed between versions |

## License

MIT. See [LICENSE](LICENSE).
