# **CS 354 Koka Group Project To-Do List**

This is a shared team tracker for the Koka website, original programs, complex team program, deployment, and presentation. Mark an item complete only when the work itself and any accosiated or required testing/review material are complete. To mark an item as complete, remove the empty space between the "[ ]" of the relative listed task, and replace it with an "x". Make sure to commit the change after doing so, or else it will not correctly update the check-list completion for everyone to see.

## Current Status and Access Notes \~

- [x] Koka selected as the group's programming language. **Team plan**
- [x] Initial member responsibilities assigned. **Team plan**
- [x] Confirm that the instructor approved Koka and record the approval email. **Assignment requirement**
- [x] Create and allow access of a shared Google Doc to each member of the group for the project. **Recommended**
- [x] Inspect the GitHub repository's current `main` branch. As of November 18, 2026, it contains only a one-line `README.md`. **Recommended**
- [x] Confirm the team's assigned ID = 1
- [x] Confirm the exact class website URL: `https://csweb.boisestate.edu/~maxtaylor/classes/354au26/teams/1/`. **Assignment requirement**


## Phase 1: Coordinate and Plan \~

- [ ] Confirm every member can reach Onyx by SSH. **Assignment requirement / prerequisite**
- [ ] Confirm every member can reach `csweb` by SSH from Onyx. `csweb` is not part of the Onyx cluster and is not reachable directly from the public Internet. **Assignment requirement / prerequisite**
- [ ] Confirm every member knows how to preview the private class website through the approved Boise State network route. **Recommended**
- [ ] Decide how website files will move from GitHub/local machines to the team's `csweb` directory. **Recommended**
- [ ] Establish a backup procedure separate from the deployed `csweb` copy. Vanished files do not qualify the team for an extension. **Assignment requirement**
- [ ] Decide the website's navigation and page structure before implementation. **Assignment requirement**
- [ ] Create a shared citation format for webpages and the presentation. **Recommended**
- [ ] Establish a review process so at least one teammate checks each section for correctness, citations, spelling, and broken links. **Recommended**
- [ ] Establish a process for recording build/run commands and tested output for every program. **Recommended**


## Phase 2: Website Structure and Shared Requirements \~

- [ ] Create a landing page that clearly identifies Koka and the team's purpose. **Assignment requirement**
- [ ] Add navigation to every required website section. **Assignment requirement**
- [ ] Add a Description and History section. Owner: **Porter Goldman**. **Assignment requirement / team plan**
- [ ] Add links to Koka's specification, documentation, manuals, and tutorials. **Assignment requirement**
- [ ] Add links to relevant academic papers. Owner: **Roberto Jones**. **Assignment requirement / team plan**
- [ ] Add translators/compiler availability and installation instructions. Owner: **Mason Beckman**. **Assignment requirement / team plan**
- [ ] Add simple original programs with build/run instructions. Owners: **Everyone**. **Assignment requirement / team plan**
- [ ] Add one or more complex example programs with build/run instructions. Owners: **Everyone collectively**. **Assignment requirement / team plan**
- [ ] Add a table comparing Koka's characteristics and features with representative languages. Owner: **Matthew Grundy**. **Assignment requirement / team plan**
- [ ] Add an Employment Prospects section. Owner: **Tyler Andrews**. **Rubric requirement / team plan**
- [ ] Make the website readable, consistently styled, and usable on common screen sizes. **Recommended**
- [ ] Add descriptive page titles, headings, link text, and image alternative text. **Recommended**
- [ ] Credit every source and distinguish quotations from paraphrases. **Recommended**


## Phase 3: Individual Contributions \~

- **Porter Goldman || *Description and History** *\~ 

    - [ ] Write a clear overview of what Koka is and what problem its effect system is designed to address.
    - [ ] Explain effect types and effect handlers in language suitable for classmates who have not used Koka.
    - [ ] Summarize Koka's major features, development history, current implementation, and present research-language status.
    - [ ] Build a short, dated history timeline supported by official sources.
    - [ ] Add useful citations at the first substantive claim they support.
    - [ ] Coordinate with Roberto so Porter's history sources and Roberto's academic-paper list complement rather than duplicate each other.
    - [ ] Ask at least one teammate to fact-check and proofread the completed section.


- **Mason Beckman || *Translators and Installation Steps** *\~ 

    - [ ] Identify the official Koka compiler/interpreter and supported platforms.
    - [ ] Link to the official Getting Started instructions and release page.
    - [ ] Provide tested installation steps for the operating systems the team claims to support.
    - [ ] List prerequisites such as VS Code/extension, Clang, or source-build dependencies only where applicable.
    - [ ] Show how to verify installation, including the expected `koka --version` or equivalent output.
    - [ ] Explain how to compile and run a `.kk` file from the command line.
    - [ ] Explain how to run examples through the recommended VS Code extension if the site documents that workflow.
    - [ ] Record the Koka version, operating system, compiler toolchain, and date used for each tested procedure.
    - [ ] Do not claim an installation path was tested unless a team member actually completed it.


- **Roberto Jones || *Documentation and Academic Papers** *\~ 

    - [ ] Link the official Koka book/specification.
    - [ ] Link the standard-library documentation.
    - [ ] Link the official repository and release history.
    - [ ] Link useful tutorials or talks from official Koka/Microsoft Research pages.
    - [ ] Create a curated academic-paper list rather than an unexplained link dump.
    - [ ] For each paper, include authors, title, year/venue or report number, link, and a one- or two-sentence relevance note.
    - [ ] Include at minimum the foundational 2013/2014 effect-types paper, the 2016/2017 algebraic-effects paper, the 2021 generalized-evidence-passing paper, and the 2021 Perceus paper. **Recommended coverage; the PDF gives no numeric minimum.**
    - [ ] Cross-check the official [Microsoft Research Koka publications index](https://www.microsoft.com/en-us/research/project/koka/publications/).


- **Matthew Grundy || *Language Comparison** *\~ 

    - [ ] Select representative comparison languages and explain why they are representative.
    - [ ] Include at least one mainstream imperative/object-oriented language and at least one functional language. **Recommended**
    - [ ] Build a clear table comparing the same characteristics across every language.
    - [ ] Compare typing discipline and type inference.
    - [ ] Compare how side effects are represented or controlled.
    - [ ] Compare error/exception handling and other control effects.
    - [ ] Compare memory management and runtime requirements.
    - [ ] Compare compilation targets, tooling, libraries/ecosystem, maturity, and intended use.
    - [ ] Explain tradeoffs in prose; avoid unsupported “better/worse” conclusions.
    - [ ] Cite factual claims and version-sensitive details.


- **Tyler Andrews || *Employment Prospects** *\~ 

    - [ ] Search for direct Koka job postings and record the search date and method.
    - [ ] If direct Koka roles are scarce, say so plainly rather than implying a large job market.
    - [ ] Explain adjacent employment value: functional programming, compiler engineering, type systems, effect systems, PL research, and related languages/tools.
    - [ ] Identify relevant employers or research areas only with evidence.
    - [ ] Distinguish current job-posting evidence from general skill-transfer analysis.
    - [ ] Cite dated, reliable sources and avoid using undated search snippets as evidence.


- **Austin || *Assistance Where Needed / To Be Determined** *\~ 

    - [ ] Assign concrete remaining work to Austin as needs become clear. Owner: **Austin**. **Team plan**
    - [ ] Review the shared tracker and claim the agreed unassigned task as needs become clear.
    - [ ] Help with website structure, integration, testing, deployment, documentation links, or presentation work as agreed by the group.
    - [ ] Record completed assistance in this checklist so the team can see the contribution and its status.


## Phase 4: Original Programs [Everyone] and Complex Team Program \~

### Individual Simple Programs \~

- [ ] Agree on the exact team target. The current plan is 2–3 simple programs per member. **Team plan**
- [ ] Ensure every member develops several original examples; do not copy Internet examples. **Assignment requirement**
- [ ] Assign unique program topics to prevent accidental duplication.
- [ ] Make each example demonstrate a meaningful Koka feature, not only altered output text.
- [ ] Include source code on the website or link it from the repository.
- [ ] Include exact build and run steps beside every program. **Assignment requirement**
- [ ] Include a short explanation of what the program demonstrates.
- [ ] Include sample input/output where useful.
- [ ] Test every documented command from a clean checkout or clean example directory.
- [ ] Record the Koka/compiler version and environment used for testing.
- [ ] Credit team authorship and list collaborators for shared examples.


### Reasonably Complex Team Program \~ 

- [ ] Meet as a team and choose a reasonably complex problem. It should be at least as difficult as one language problem from the course homework, but not unmanageably difficult. **Assignment requirement**
- [ ] Write a concise problem statement and acceptance criteria before implementation.
- [ ] Divide the problem so every member has approximately the same amount of work. **Assignment requirement**
- [ ] Record ownership of modules/features and integration responsibilities.
- [ ] Agree on interfaces and shared data types before parallel implementation.
- [ ] Implement each member's assigned portion.
- [ ] Integrate all portions into one working solution. **Assignment requirement**
- [ ] Add representative tests, sample inputs, and expected outputs.
- [ ] Document exact build/run instructions on the website. **Assignment requirement**
- [ ] Explain the design and which Koka features the program demonstrates.
- [ ] Record challenges, surprises, limitations, and lessons for the presentation.
- [ ] If the group also wants one smaller “complex” program per member, track those separately; the assignment itself explicitly describes one partitioned team problem for Part 2.


## Phase 5: Website Verification and Deployment \~ 

- [ ] Confirm every 40-point website rubric category is visible and easy to find:
    - [ ] Description/history - 5 points.
    - [ ] Documentation and academic-paper links - 5 points.
    - [ ] Translators/installation steps - 5 points.
    - [ ] Simple programs with build/run steps - 5 points.
    - [ ] More complex programs - 5 points.
    - [ ] Language comparison - 10 points.
    - [ ] Employment prospects - 5 points.
- [ ] Check every internal navigation link.
- [ ] Check every external source link.
- [ ] Check that every code example is original and attributed to its team author(s).
- [ ] Re-run every program and verify the documented commands and output.
- [ ] Check the site in at least two browsers or rendering engines. **Recommended**
- [ ] Check narrow and wide screen layouts. **Recommended**
- [ ] Proofread names, terminology, headings, captions, and citations.
- [ ] Confirm that no private credentials, tokens, local paths, or unrelated files are published.
- [ ] Deploy the final site to the assigned `csweb` team directory.
- [ ] Verify the deployed site from Onyx/the approved network path, not only from a local preview.
- [ ] Create and verify a final independent backup of the deployed website and source repository.


## Phase 6: Team Presentation \~ 

- [ ] Plan a team presentation of about 30 minutes for the final class meetings. **Assignment requirement**
- [ ] Briefly introduce Koka. **Assignment guidance**
- [ ] Clearly specify the reasonably complex problem. **Assignment guidance**
- [ ] Explain the solution and how the team partitioned/integrated it. **Assignment requirement / rubric**
- [ ] Describe the team's experience solving the problem, including what was easy, difficult, surprising, or incomplete. **Assignment guidance**
- [ ] Create clear visual aids. **Rubric: 5 points**
- [ ] Organize the opening and introduction so the presentation has a coherent through-line and invites questions/discussion. **Rubric: 5 points**
- [ ] Assign speaking roles and make every transition explicit. **Recommended**
- [ ] Rehearse for good volume, clear pronunciation, and responses to likely questions; do not simply read slides. **Rubric: 5 points**
- [ ] Rehearse the full talk and keep it within the time limit. **Rubric: 3 points**
- [ ] Prepare a reliable live demo or a tested fallback such as screenshots/output captures. **Recommended**
- [ ] Verify that the problem description is clear. **Rubric: 5 points**
- [ ] Verify that the solution description is clear. **Rubric: 5 points**
- [ ] Remember that the presentation itself is not submitted; the instructor grades it as it happens. **Assignment note**


## Final Completion Checks \~ 

- [ ] All website rubric categories are complete and reviewed.
- [ ] Every member contributed several original examples.
- [ ] Every published program has verified build/run instructions.
- [ ] The complex team solution is integrated and demonstrably works.
- [ ] All claims and borrowed material have useful citations.
- [ ] The deployed site works through the required Boise State access path.
- [ ] A separate current backup exists.
- [ ] The 30-minute team presentation has been rehearsed and meets every presentation rubric item.
- [ ] The team has completed one final rubric-by-rubric audit.


## Potential Sources \~ 

- [ ] [Microsoft Research Koka overview](https://www.microsoft.com/en-us/research/project/koka/overview/) - use the Overview and People sections for the April 13, 2012 establishment date, Daan Leijen, the language summary, effect handlers, evidence translation, and Perceus.
- [ ] [The Koka Programming Language book](https://koka-lang.github.io/koka/doc/book.html) - use “Getting started” for current status and compiler use, and “Why Koka?” for the modern design overview. This is also the principal language tour/specification.
- [ ] [Koka: Programming with Row-polymorphic Effect Types](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/koka-effects-2013.pdf) - use PDF page 1 (abstract, Introduction, and footnote 1) for effect typing, automatic inference, early examples, and the name's meaning; Microsoft Research technical report MSR-TR-2013-79, August 28, 2013.
- [ ] [Algebraic Effects for Functional Programming](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/08/algeff-tr-2016-v2.pdf) - use PDF page 1 (abstract and Introduction) for Koka's practical algebraic effects, effect handlers, row typing, and the then-current compilation approach; MSR-TR-2016-29, August 2016.
- [ ] [Generalized Evidence Passing for Effect Handlers](https://www.microsoft.com/en-us/research/wp-content/uploads/2021/03/multip-tr-v2.pdf) - use PDF page 1 (abstract and Introduction) for the later effect-handler compilation pipeline and Koka C backend; MSR-TR-2021-5, April 2021.
- [ ] [Perceus: Garbage Free Reference Counting with Reuse](https://www.microsoft.com/en-us/research/wp-content/uploads/2021/06/perceus-pldi21.pdf) - use PDF page 1 (abstract and Introduction) for Perceus, reference counting, reuse analysis, and its Koka implementation; PLDI 2021.
- [ ] [Official Koka release history](https://github.com/koka-lang/koka/releases) - use dated release entries for version-specific timeline claims; record the access date because releases change.
- [ ] [Official Koka repository](https://github.com/koka-lang/koka) - use the README's Branches section to distinguish the old Koka v1 JavaScript/C# backend from current development.



