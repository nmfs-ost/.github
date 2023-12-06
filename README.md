# Branding for a NMFS GHEC organization

## Organization settings

Edit the [organization settings](https://docs.github.com/en/enterprise-cloud@latest/organizations/collaborating-with-groups-in-organizations/accessing-your-organizations-settings) (settings tab when you are on the organization page):

1. Logo. If this is the organization for a science center or regional office, use [the digital NOAA logo](https://drive.google.com/drive/folders/17QrjaWNvm4Tfhd3JdML6Kc2r8px4VE1O). You will need to download and then upload this as a profile picture. If this is for a cross-office program or initiative, use the logo for that.
2. URL. Use the url to the office on fisheries.gov. For example, `https://www.fisheries.noaa.gov/about/pacific-islands-regional-office`
3. Email. If your GitHub org has an email, include that here. Otherwise, the github.governance.team@noaa.gov service email can be used here.
4. Description. If your organization has a `profile/README.md` file, then you can leave this blank. Otherwise include a short description like "GitHub organization and repositories from staff of the NWFSC" or "GitHub organization for the Fisheries Integrated Toolbox"

## Optional: Create a organization profile README

[Organization profiles](https://docs.github.com/en/enterprise-cloud@latest/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile#organization-profile-readmes) show information about your org publicly on GitHub.

If you create a `.github` public repository within the organization and create a `README.md` file in a folder called `profile`, that markdown will appear when you go to the organization page. A link to create this will probably come up on the right side of your organization if you have not created this file yet.

The `.github` repository needs to be public for the `profile/README.md` file to be used as the Organization Profile.

### Template for org profile readme

Below is a template `README.md` file to be put in the  `.github/profile` folder.

```
# Full office name

short statement of what the org is for

Names of admins or an email for the org

---

Optional extra info for example links to popular repos or topic searches. You can also insert a table with the name, short description, and last commit of the repositories as seen in [this repo](https://github.com/pfmc-assessments/.github/blob/main/profile/README.md) (that isn't in GHEC) from staff at SWFSC and NWFSC.

## Disclaimer

The repositories in this GitHub org are scientific products and are not official communication of the National Oceanic and Atmospheric Administration, or the United States Department of Commerce. All NOAA GitHub project code is provided on an ‘as is’ basis and the user assumes responsibility for its use. Any claims against the Department of Commerce or Department of Commerce bureaus stemming from the use of this GitHub project will be governed by all applicable Federal law. Any reference to specific commercial products, processes, or services by service mark, trademark, manufacturer, or otherwise, does not constitute or imply their endorsement, recommendation or favoring by the Department of Commerce. The Department of Commerce seal and logo, or the seal and logo of a DOC bureau, shall not be used in any manner to imply endorsement of any commercial product or activity by DOC or the United States Government
```

### Example of an org profile readme

See [here](https://github.com/nmfs-ost/.github/blob/main/profile/README.md) for an example of what the below code looks like as a README.md for the Office of Science and Technology.

```
# NOAA Fisheries - Northwest Fisheries Science Center

This GitHub organization is for members of the [Northwest Fisheries Science Center (NWFSC)](https://www.fisheries.noaa.gov/about/northwest-fisheries-science-center) and their collaborators. 

Contact: nwfsc-github-admin@noaa.gov

---

How to find repositories? Click on repositories tab and search for a topic (marine mammals, stock assessment, genetics, etc), division name (FRAM, CB, FE) or program (e.g. Math Bio, Genetics, Ecosystem). 

## Disclaimer

The repositories in this GitHub org are scientific products and are not official communication of the National Oceanic and Atmospheric Administration, or the United States Department of Commerce. All NOAA GitHub project code is provided on an ‘as is’ basis and the user assumes responsibility for its use. Any claims against the Department of Commerce or Department of Commerce bureaus stemming from the use of this GitHub project will be governed by all applicable Federal law. Any reference to specific commercial products, processes, or services by service mark, trademark, manufacturer, or otherwise, does not constitute or imply their endorsement, recommendation or favoring by the Department of Commerce. The Department of Commerce seal and logo, or the seal and logo of a DOC bureau, shall not be used in any manner to imply endorsement of any commercial product or activity by DOC or the United States Government
```

## Optional: Create a member-only profile readme

[Member-only profile readmes](https://docs.github.com/en/enterprise-cloud@latest/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile#adding-a-member-only-organization-profile-readme) show up just for organization members on the organization's landing page. This may be a good place to provide internal information, such as links to the org SOP or instructions on how to submit requests to administrators.
