---
layout: default
title: Digitization
parent: Franz Lab
has_children: true
nav_order: 2
---


# Digitization
{: .no_toc }

Digitization workflows for the weevil collection. Data publicly available on [GBIF](https://www.gbif.org/dataset/aae308f4-9f9c-4cdd-b4ef-c026f48be551). 
{: .fs-5 .fw-300 }

---

<div class="code-example" markdown="1">

<span class="fs-5">
New secimens should be **accessioned** before digitization.
</span>

</div>


## Digitizing specimens

- Access the Specify [KUEntoPinned](https://entomology.specify.ku.edu) instance. Coordinate with collection managers to get access.

| [<img src="https://github.com/user-attachments/assets/f5c4854a-d069-4c12-bc3b-199d356c7df2" alt="Event Query"  width="480" height="500">](https://entomology.specify.ku.edu/) |

{: .highlight }
Select the specimen(s) to digitize and prepare the **catalog numbers** (barcodes). If specimens have been collected recently (e.g. current Franz Lab projects), make sure they are **accessioned** before digitizating. Coordinate with collection managers to get appropriate paperwork.

| [<img src="https://github.com/user-attachments/assets/31f88073-e8f3-4485-a888-1f79dd2dbdda" alt="Labels"  width="480" height="500">](https://entomology.specify.ku.edu/) |

### Check data on the label
**What do you see? **
- Country, state, county, locality?
- Coordinates, elevation?
- Date?
- Collector(s)?
- Habitat, collecting method?
- Field numbers?

Every label is different. Don't worry if some elements are missing. 

To digitize a specimen in Specify, you need two codes: a unique _catalog number_ (barcodes), and a _collecting event number_, that will be shared by all specimens collected during the same fieldtrip in a particular date, by the same collector(s), with the same method. For example, all insects collected by N. Franz during the night of Aug 24, 2005 would share the same _collecting event number_.  

The **catalog numbers** (barcodes) are printed and provided by the collection managers. The **collecting event numbers** are generated in advance by the researchers OR are asigned by  the person in charge of digitization, in the case of older specimens. 


| [<img src="https://github.com/user-attachments/assets/7b107c3a-1707-4361-b501-0cca97905eea" alt="CollEvUS"  width="480" height="500">](https://entomology.specify.ku.edu/specify/view/collectingevent/125414/) |

| [<img src="https://github.com/user-attachments/assets/340d8220-116d-4fa7-9bfd-2fb73d1e477b" alt="CollEvPanama"  width="480" height="500">](https://entomology.specify.ku.edu/specify/view/collectingevent/1994/) |

---


-   Explore the existing _collecting events_, which should match for locality, date, collector and method. Collecting events for 2025 fieltrips available [here](https://kansas.sharepoint.com/:x:/t/FranzLab/ERPYc_iq79lCkkPA7ZNbF6gB6hQDf9rCABoX3qKdrw8KLQ?e=x7YMvO).

Suggested query:

| [<img src="https://github.com/user-attachments/assets/976753cd-7fc5-4dbc-a3a0-b836ac9b91af" alt="Event Query"  width="480" height="500">](https://entomology.specify.ku.edu/specify/query/521/) |

- If the _collecting event_ is not available, check for the locality.  


| [<img src="https://github.com/user-attachments/assets/4b3f9dd8-5c0a-4347-9dca-8379d4678a5c" alt="Locality Query"  width="480" height="500">](https://entomology.specify.ku.edu/specify/query/524/) |

- If the locality doesn't exist, generate a new one. 

| <img src="https://github.com/user-attachments/assets/e56ef1f7-d124-4b1d-a91e-9df769e3efcf" alt="New Locality"  width="480" height="500"> |

Example:

![LocalityExample](https://github.com/user-attachments/assets/1d69e8ae-caeb-43d5-a37c-355a2b9e09da)


