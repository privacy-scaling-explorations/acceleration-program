# Project Ideas

If you are PSE research team member. Please submit your ideas below using the template. After uploading your idea, run this command to refresh the table of contents.

```shell
cat ./Open-Task-RFP/Open-Task-RFP-List.md | ./gh-md-toc - > ./Open-Task-RFP/table-of-contents.md
```

P.S. `gh-md-toc` is an opensource software from [here](https://github.com/ekalinin/github-markdown-toc)

## What Constitute an Ideal Open Task RFP?

The structure of this program’s Open-Task will include both bounty-style Open Task RFP and open-style Open Task RFP.

For **bounty-style Open Task RFP**, we will list out specific ideas that we are seeking individuals to work on. Here are some examples of this type of Open Task RFP:

- Create a Halo2 tutorial.
- Snark mobile proving kit.

    Make a Halo2 aggregation toolbox: a simple tool to let ppl merge proofs, prove them, and make a verifier.

For **open-style Open Task RFP**, we will list out relatively open questions that we are seeking individuals to explore further with. Here are some examples of this type of Open Task RFP:

- Differential privacy projects.

    Study differential privacy for zkstarts , mpc stats and zkpipes ideas. Can we design a VM that leakes 0 info but allows meaningful communications?

- Folding Scheme.

    Study folding schemes and research potential use cases.

For the initial iterations of this program, **we will start with the more specific bounty-style first**, as it allows us to develop the program in a more calculated manner.

---

## Template

```markdown
### Title (Project Name if any)

### Open Task RFP for [Project Title]

#### Executive Summary

- Project Overview: Briefly describe what the project is about and its primary objectives.
  
#### Project Details

- Scope of Work: Outline the specific tasks, milestones, and deliverables expected from this project.
- Expected Outcomes: Clearly state what successful completion of the project looks like.
- Technical Requirements: List any specific technologies, frameworks, or tools that will be needed.

#### Qualifications

- Skills Required: Detail the skills and experience that would make a candidate well-suited for this project.
- Preferred Qualifications: Any additional skills or experience that would be a plus.

#### Administrative Details

- Grant Liaison(s): Name, GitHub, email of the person(s) responsible for evaluating and keeping track of this project.
- Estimated Project Duration: Timeframe for project completion, including any key deadlines.
- Project Complexity: Rate the project's difficulty level as Easy, Medium, or Hard. Explain the reasons for this.

#### Additional Information

- Relevant Tags: Keywords to help categorize the project (e.g., FHE, MPC, ZKPs).
- Reference Material: Links to any upstream issues, documentation, or other resources that provide more context.

#### Submission Details

- Proposal Deadline: Specify the last date for proposal submissions.
- Submission Instructions: Explain how and where to submit proposals.
```

---

### Mobile GPU Prover

- Description: make an msm work on mobile GPU.
- Expected outcome:
- Recommended Skills: Rust, CUDA
- Grant Liason(s): (Name, github, email)
- Expected project size: (Hours)
- Difficulty: (Easy, Medium, or Hard)
- Tag: Mobile
- Upstream Issue (URL): N/A
- Submission (Update) Date: 2023/09/13

### RSA GitHub wallets POC

- Description: Make transfers with gitcommits and pill requests
Update stare of repo via continuous integration
- Expected outcome:
- Recommended Skills: Rust, CUDA
- Grant Liason(s): (Name, github, email)
- Expected project size: (Hours)
- Difficulty: (Easy, Medium, or Hard)
- Tag: Mobile
- Upstream Issue (URL): N/A
- Submission (Update) Date: 2023/09/13

### Quantum computer canary and safe exit

- Description: Make transfers with gitcommits and pill requests
Update stare of repo via continuous integration
- Expected outcome:
- Recommended Skills: Rust, CUDA
- Grant Liason(s): (Name, github, email)
- Expected project size: (Hours)
- Difficulty: (Easy, Medium, or Hard)
- Tag: Mobile
- Upstream Issue (URL): N/A
- Submission (Update) Date: 2023/09/13

### Plonk by hand , Nova by hand

- Description: An implementation / tutorial that ppl can build by themselves plonk / nova / other stuff
- Expected outcome:
- Recommended Skills: Cryptography
- Grant Liason(s): (Name, github, email)
- Expected project size: (Hours)
- Difficulty: (Easy, Medium, or Hard)
- Tag: Tutorial
- Upstream Issue (URL): N/A
- Submission (Update) Date: 2023/09/21

### Snark mobile proving kit

- Description: Like websnark for mobile using GPU , tpu to make proofs asap
- Expected outcome:
- Recommended Skills: Cryptography
- Grant Liason(s): (Name, github, email)
- Expected project size: (Hours)
- Difficulty: (Easy, Medium, or Hard)
- Tag: Tutorial
- Upstream Issue (URL): N/A
- Submission (Update) Date: 2023/09/21

### A snark to prove that below a number X there are y prime numbers and no more

- Description: Maybe this is similar to doing a proof of unsat
- Expected outcome:
- Recommended Skills: Cryptography
- Grant Liason(s): (Name, github, email)
- Expected project size: (Hours)
- Difficulty: (Easy, Medium, or Hard)
- Tag: Cryptography
- Upstream Issue (URL): N/A
- Submission (Update) Date: 2023/09/21

### halo2 aggregation toolbox

- Description: make a halo2 aggregation toolbox just a simple tool to let ppl merge proofs , prove them and make verifier
- Expected outcome:
- Recommended Skills: halo2
- Grant Liason(s): (Name, github, email)
- Expected project size: (Hours)
- Difficulty: (Easy, Medium, or Hard)
- Tag: Tooling
- Upstream Issue (URL): N/A
- Submission (Update) Date: 2023/09/21

### halo2 soundness bugs examples
- Description: Create a repository with small halo2 circuits where each one has a different soundness bug.  Add exploiting example for each.  This can be useful to:
Train people to understand the bugs to avoid them
Train people to spot the bugs. Refer to this url:
https://github.com/0xPARC/zk-bug-tracker#common-vulnerabilities-header
- Expected outcome:
- Recommended Skills: halo2
- Grant Liason(s): ed255
- Expected project size: (Hours)
- Difficulty: (Easy, Medium, or Hard)
- Tag: Tooling
- Upstream Issue (URL): N/A
- Submission (Update) Date: 2023/09/21