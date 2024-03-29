# speaker notes

# bullet points

- welcome
    - im nils
    - talk about how to contribute to the rust project
    - esteban rustconf 3 years ago
    - you in 3 years!
- whoami
    - nils, compiler contributors team
    - helping people, triaging, shitposting on discord
    - 1.72 cfg
- others
    - reviewed the talk
    - important path of why I contribute
    - friends reviewing your PRs
- start
    - some contributed before
    - wanted to but never have
    - many ways, no matter experience
    - some domain-expecific expertise
    - some no knowledge of rust
    - will learn something
    - requirement: time and interest
- what to contribute?
    - where to get started?
- not code
    - usual focus on code
    - rust also not good, thanks.rust-lang.org
- triage
    - easy to get started
    - variable amounts of time
    - labelling, minimization, bisection, adding tests
- labelling
    - helps with
        - organizing issues
        - finding related issues
    - least time
    - std document mmeory ordering thread::spawn
    - feature request, documentation, threads, atomics, libs api
    - -needs-triage +A-docs +T-libs-api +C-feature-request +A-thread +A-atomics
    - A- , T-, C-
    - use rustbot
    - see link
- bisect
    - helps with
        - finding the root cause of the problem
        - figure out when regression happened -> priorization
    - E-needs-bisect (not only)
    - ICE easiest
    - cargo-bisect-rustc (--access github)
    - start date, often last year or last few months
    - issue comment
    - potential problems
        - feature
- minimization
    - helps with
        - debugging
        - coming up with a test
    - E-needs-mcve
    - me in 2 hours to 60 lines, on github
    - felix (compiler team) blog post (outdated)
    - cargo-minimize
    - helps you learn more about rust
    - starting point for fixing
- adding tests
    - E-needs-test
    - fixed, no test
    - commit test
- existing unstable features
    - a lot of unstable features
    - used some or many of them, a favourite
    - goal: stabilize or close
- tracking issues
    - C-tracking-issue
    - over 700
    - dont new
    - really old -> problems
    - middle
- summarize
    - most important: summarize discussion
    - aggregate open and resolved questions
    - propose next steps, suggest answers
- stabilization report
    - no open questions
    - proportional to amont of discussion
    - team takes a look
- close
    - use cases haven't proven themselves
    - subseeded by other feature
    - also summarize discussion
- fcps
    - team decisions
    - majority approves
- writing code
    - want to write code
    - lots of code
- official tooling
    - very good, but needs help
    - different, choose
    - fix bugs, implement new features (like lints)
- standard library
- compiler
    - me
    - diagnostics (many, many)
    - internal compiler error fixes (variable difficulty)
    - E-mentor
- diagnostics
    - my first
    - search for issue, fix it
- examples
- rustc dev guide
- looking at PRs
    - if unsure
    - know what's happening
    - learn from others
    - do leave comments
- to remember
    - many volunteers, no guaranteed review time
- ask for help on zulip
- end
    - i hope i was able to encourage some of you to get started
    - for others, learn how rust works
    - questions
