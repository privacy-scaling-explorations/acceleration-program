# acceleration-program
# Purpose

The purpose of this grant program is to help enable the potential of those who recently started their journey in the world of ZKPs. Specifically, our goal is to:

1. **Lower the entry barrier for ZKP research**
    
    For many people, it is not clear how to get started with ZKP research, and we want this program to be a menu of options for those interested in going deeper. We aim for this program to encourage people in the community to take on the challenge of attaining a deeper understanding of ZKPs.
    
2. **Encourage domain expertise development**
    
    Many people go through a ZK-focused course or program (e.g. zkPlayground or the Summer Contribution Program) and may not have the resources to continue their learning in a specific direction after the program ends.
    
    With this grant, we would like to support them to continue building deeper knowledge and skills into more specific areas of research and eventually become a domain expert.
    

# Program Summary

Ideas for grants are submitted as Request for Proposals (RFPs) into a Github repository by Barry or PSE Team leads. Potential grantees will then submit proposals to be evaluated by “Grant Liaisons”. A grant liaison will not only evaluating the initial proposal, but will also be supervising milestone completion, approving disbursement of funds, ongoing tracking/advising and general oversight of an awarded grant.

# Grant Types

The structure of this program’s grant will include both bounty-style grants and open-style grants.

For **bounty-style grants**, we will list out specific ideas that we are seeking individuals to work on. Here are some examples of this type of grant:

- Create a Halo2 tutorial.
- Snark mobile proving kit.

    Make a Halo2 aggregation toolbox: a simple tool to let ppl merge proofs, prove them, and make a verifier.
    

For **open-style grants**, we will list out relatively open questions that we are seeking individuals to explore further with. Here are some examples of this type of grant:

- Differential privacy projects.
    
    Study differential privacy for zkstarts , mpc stats and zkpipes ideas. Can we design a VM that leakes 0 info but allows meaningful communications?
    
- Folding Scheme.
    
    Study folding schemes and research potential use cases.
    

For the initial iterations of this program, **we will start with the more specific bounty-style first**, as it allows us to develop the program in a more calculated manner.

# Operational Platform

For the operation of this program, we will primarily utilize a Github repository for managing documents and staging of the grant proposals, grantees, and their progress. Stakeholders involved can utilize Github issues and pull requests to comment and collaborate. 

# Grant Life Cycle (process flow)

![截圖 2023-08-28 下午7.42.11.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a6d8a6ba-fa6f-464d-8042-2956bac41dc2/%E6%88%AA%E5%9C%96_2023-08-28_%E4%B8%8B%E5%8D%887.42.11.png)

The diagram above illustrates the general life cycle of a grant from the formation of an idea as an RFP all the way to the execution of an initial milestone. Some of these details are clarified further here:

1. **Idea Sourcing and Request For Proposals (RFP)**
    1. Barry and PSE team leads can add their ideas directly to the [repo](https://github.com/NOOMA-42/sample-pse-small-grant) mentioned above in the form of an RFP.
    2. The format of these RFPs is yet to be determined, but there are industry standard templates that EcoDev will build on top of. We will draft an RFP template based on feedback from the wider PSE team.
2. **Applicant Selection**
    1. Applicants will be solicited to evaluate the list of available RFPs and submit their proposal along with relevant milestones as an issue or PR to the [repo](https://github.com/NOOMA-42/sample-pse-small-grant).
    2. Applicants may refer to application guidelines in [repo](https://github.com/NOOMA-42/sample-pse-small-grant) (Format TBD, maybe similar to [Google Summer of Code](https://github.com/oppia/oppia/wiki/Google-Summer-of-Code-2023#types-of-work-related-to-oppia-projects)). Again, the specifics of this will be further developed by the EcoDev team.
    3. In the case where multiple applicants are interested in the same RFP, we shall consider one of the following options:
        1. Evaluate them at the same time (i.e. round-style with a deadline for submission).
        2. Evaluate them on a first-come first-serve basis.
        3. Other. We might have to consider these proposals on a case-by-case basis.
            1. If all the applicants meet the criteria, we might consider grant multiple applicants.
3. **Grant Liaison Matching**
    1. Internally we maintain an evaluator availability list and their domain expertise along side of their names. EcoDev will work with leadership and project leads to determine the appropriate candidate to be an evaluator.
4. **Milestone Completion and Funding**
    1. Grantee will receive a small amount of funding after the completion of the first milestone.
    2. Following milestones will be awarded larger amounts.
    3. Stale issues will be closed by grant liaison or a bot.