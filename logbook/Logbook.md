# PHS3350 Summer Project
 
 > [!note] Project Info
 > **Spin-Orbit Misalignments of Hot Jupiters around Old Stars**
 > Supervisor: Dr. Evgeni Grishin ([eugeneg88](https://github.com/eugeneg88))
 > Period: Summer A 2026/27

## Current Tasks
- [ ] Set up Slack
- [ ] Replicate Evgeni's plots using his GitHub code
- [ ] Research Wu & Murray 2003.

### 05/11/26 - Preliminary preparation and research

- Prior to today, I had a look at Prof Tremaine's Celestial Mechanics I lecture as well as a paper ([Eccentric Kozai-Lidov Effect](../references/1601.07175v1.pdf)). I also played around a little with `REBOUND` in both Python and C to get a feel of how to use it.
- Yesterday I met with Evgeni and we discussed more of what I would be working on. He suggested a project title of "Spin-Orbit Misalignments of Hot Jupiters around Old Stars" which I submitted to the enrolment form.
- From now until most of the rest of November, Evgeni is on leave and I have exams, so we agreed to lower expectations until then. Meanwhile, if I have time and definitely after exams I will be:
  - Working on understanding Evgeni's code `SecuLab` which I forked. So far I have not changed anything except its overall file structure so I can package and run it using `uv`, my chosen Python environment manager.
    - I will probably end up starting with a full rewrite of his code. My initial idea is to design an object-oriented version of it that replicates its behaviour, then profile it and rewrite the bottlenecks in C++ (likely the integration loop) or even possibly Rust if I have the time or want to take this opportunity to learn.
  - Research into misaligned hot Jupiter orbits ([Wu & Murray 2003](../references/wumurray2003.pdf)).
