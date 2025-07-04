# Tutorial 6: Digital Object Identifiers for your Github Data
------------------------------------------------------------------
## Overview
There are a few tools and platforms that offer DOI creation for files, datasets, or software associated with GitHub. However, **Zenodo** is the most widely known and trusted service for assigning DOIs to GitHub-hosted content. Thus, this tutorial will focus on using this tool.

## Learning Objectives
After completing this tutorial, you will be able to:
- Understand the purpose of a DOI in scholarly communication and FAIR data compliance.
- Identify Zenodo as a trusted research data repository for archiving GitHub-hosted data and software
- Create and connect a Zenodo account to GitHub to enable DOI generation.
- Prepare a GitHub repository for archiving, including adding a README, license, and release.
- Create a formal GitHub release that can be archived and assigned a DOI.
- Locate and cite the DOI generated by Zenodo for their release.

## Prerequisites
Please complete tutorials 4 and 5 in advance.

-----------------------------------------------------------------
## Introduction
A DOI (Digital Object Identifier) provides a persistent, globally unique, and **citable reference** to a specific version of your dataset or software. Under the FAIR data principles—Findable, Accessible, Interoperable, and Reusable—DOIs play a critical role in ensuring that:

🔎 Findable: Data can be reliably located through metadata indexing services like DataCite or CrossRef.

🔗 Accessible: A DOI ensures there’s a stable link to a publicly available version (or metadata record).

📚 Reusable: Citation via DOI promotes proper attribution, credit, and encourages ethical data reuse.

🧬 Versioned and Documented: DOIs can be assigned to specific releases of data/software, creating an auditable research trail.

In short, DOIs support transparency, reproducibility, and proper data citation, making them a key element of FAIR-aligned research.

[Zenodo.org](https://zenodo.org/) is a free, reputable platform maintained by CERN and OpenAIRE. It integrates with GitHub to automatically archive releases and assign a DOI.

## ✅ Step-by-Step Instructions

1. Prepare Your GitHub Repository
Make sure your repository has:
- A clear README.md (describing the project or data).
- A LICENSE file (open licenses like MIT, CC-BY, etc. are recommended). See [Github](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/adding-a-license-to-a-repository)
- A versioned release (Zenodo will archive specific releases, not your live repo). See [Github](https://docs.github.com/en/repositories/releasing-projects-on-github/managing-releases-in-a-repository)

2. Create a Zenodo Account
- Go to https://zenodo.org
- Click Sign In (you can use your GitHub, ORCID, or other credentials).

Once signed in, go to your Dashboard.

3. Connect Your GitHub Account to Zenodo
- Go to Zenodo GitHub Settings
- Click Connect GitHub.
- Authorize Zenodo to access your GitHub account.

You’ll see a list of your repositories—flip the toggle to enable archiving for the repo you want to assign a DOI.

4. Create a GitHub Release
**DOIs are generated only for releases, not for every commit.**

- In your GitHub repository, click the "Releases" tab.
- Click “Draft a new release”.
- Tag it with a version number (e.g., v1.0.0).
- Add a title and description (e.g., “Initial release of dataset”).
- Click Publish release.

Zenodo will automatically archive this release and assign a unique DOI.

5. Find Your DOI on Zenodo
- Go back to Zenodo.org
- Click Dashboard → Uploads or GitHub
- Click on your project

You’ll see a permanent DOI like this:

**10.5281/zenodo.1234567**

This DOI is now persistent, citable, and indexed.

-----------------------------------------------------------------------
## Conclusion

You have finished the introductory tutorial that enables you to use GitHub to retrieve tutorials and to use its features for version control of your own data. 

The next submodule will begin your Introduction to Python programming!